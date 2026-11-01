---
title: "add_link methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Voegt een bijlage toe via een link (het document bevat geen bijgevoegde bestandsinhoud)."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Voegt een bijlage toe via een link (het document bevat geen bijgevoegde bestandsinhoud).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_full_name | `str` | Het gekoppelde bestandspad. |
| preview_image_content | `list[int]` | De voorbeeldafbeelding van het bijgevoegde bestand als byte‑array. |
| x | `float` | De x-coördinaat van het bijlage‑frame (in punten). |
| y | `float` | De y-coördinaat van het bijlage‑frame (in punten). |
| width | `float` | De breedte van het bijlageframe in punten. |
| height | `float` | De hoogte van het bijlageframe in punten. |

### Voorbeeld

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

### Zie ook
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
