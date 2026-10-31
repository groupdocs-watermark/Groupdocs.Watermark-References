---
title: "add_link μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Προσθέτει ένα συνημμένο μέσω συνδέσμου (το έγγραφο δεν θα περιέχει το περιεχόμενο του συνημμένου αρχείου)."
type: docs
url: /el/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Προσθέτει ένα συνημμένο μέσω συνδέσμου (το έγγραφο δεν θα περιέχει το περιεχόμενο του συνημμένου αρχείου).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_full_name | `str` | Η διαδρομή του συνδεδεμένου αρχείου. |
| preview_image_content | `list[int]` | Η εικόνα προεπισκόπησης του συνημμένου αρχείου ως πίνακας byte. |
| x | `float` | Η x‑συντεταγμένη του πλαισίου συνημμένου (σε σημεία). |
| y | `float` | Η y‑συντεταγμένη του πλαισίου συνημμένου (σε σημεία). |
| width | `float` | Το πλάτος του πλαισίου συνημμένου σε μονάδες σημείου. |
| height | `float` | Το ύψος του πλαισίου συνημμένου σε μονάδες σημείου. |

### Παράδειγμα

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    worksheet = content.worksheets[0]
    with open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_link(
            "document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("output.xlsx")
```

### Δείτε επίσης
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
