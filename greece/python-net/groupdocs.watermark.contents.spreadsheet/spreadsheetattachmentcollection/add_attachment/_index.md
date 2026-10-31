---
title: "add_attachment μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Προσθέτει ένα συνημμένο στο SpreadsheetWorksheet."
type: docs
url: /el/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Προσθέτει ένα συνημμένο στο SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_content | `list[int]` | bytes που περιέχουν το περιεχόμενο του αρχείου που θα προσαρτηθεί. |
| source_full_name | `str` | str πλήρες όνομα του συνημμένου αρχείου (η επέκταση χρησιμοποιείται για τον καθορισμό της κατάλληλης εφαρμογής για το άνοιγμα του αρχείου). |
| preview_image_content | `list[int]` | bytes εικόνα προεπισκόπησης του συνημμένου αρχείου ως πίνακας byte. |
| x | `float` | int x‑συντεταγμένη του πλαισίου συνημμένου (σε σημεία). |
| y | `float` | int y‑συντεταγμένη του πλαισίου συνημμένου (σε σημεία). |
| width | `float` | int πλάτος του πλαισίου συνημμένου (σε σημεία). |
| height | `float` | int ύψος του πλαισίου συνημμένου (σε σημεία). |

**Returns:** None.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def add_attachment():
    with Watermarker("./sample.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        with open("./sample.docx", "rb") as f:
            data = f.read()
        with open("./preview.png", "rb") as f:
            preview = f.read()
        # Ενσωματώστε το αρχείο στο πρώτο φύλλο εργασίας, εμφανιζόμενο ως η εικόνα προεπισκόπησής του
        # στο x=50, y=20 με πλαίσιο 100 x 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Δείτε επίσης
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
