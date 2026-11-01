---
title: "add_attachment‑metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Lägger till en bilaga till SpreadsheetWorksheet."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Lägger till en bilaga till SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_content | `list[int]` | byte som innehåller innehållet i filen som ska bifogas. |
| source_full_name | `str` | str fullständigt namn på den bifogade filen (filändelsen används för att bestämma lämplig applikation för att öppna filen). |
| preview_image_content | `list[int]` | byte för förhandsgranskningsbilden av den bifogade filen som en byte‑array. |
| x | `float` | int X‑koordinat för bilagans ram (i punkter). |
| y | `float` | int Y‑koordinat för bilagans ram (i punkter). |
| width | `float` | int bredd på bilagans ram (i punkter). |
| height | `float` | int höjd på bilagans ram (i punkter). |

**Returns:** None.

### Exempel

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
        # Bädda in filen i det första kalkylbladet, visas som dess förhandsgranskningsbild
        # vid x=50, y=20 med en 100 x 120 ram
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Se även
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
