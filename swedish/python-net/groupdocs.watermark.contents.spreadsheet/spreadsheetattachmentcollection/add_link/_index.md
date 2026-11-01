---
title: "add_link metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Lägger till en bilaga via en länk (dokumentet kommer inte att innehålla bilagt filinnehåll)."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Lägger till en bilaga via en länk (dokumentet kommer inte att innehålla bilagt filinnehåll).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_full_name | `str` | Den länkade filsökvägen. |
| preview_image_content | `list[int]` | Förhandsgranskningsbilden för den bifogade filen som en bytearray. |
| x | `float` | X‑koordinaten för bilagans ram (i punkter). |
| y | `float` | Y‑koordinaten för bilagans ram (i punkter). |
| width | `float` | Bredden på bifogningsramen i punkter. |
| height | `float` | Höjden på bilagans ram i punkter. |

### Exempel

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

### Se även
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
