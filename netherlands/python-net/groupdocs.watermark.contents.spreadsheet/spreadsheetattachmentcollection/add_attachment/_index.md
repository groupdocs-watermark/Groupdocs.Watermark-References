---
title: "add_attachment methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Voegt een bijlage toe aan de SpreadsheetWorksheet."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Voegt een bijlage toe aan de SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_content | `list[int]` | bytes die de inhoud van het bij te voegen bestand bevatten. |
| source_full_name | `str` | str volledige naam van het bijgevoegde bestand (de extensie wordt gebruikt om de juiste toepassing te bepalen om het bestand te openen). |
| preview_image_content | `list[int]` | bytes voorbeeldafbeelding van het bijgevoegde bestand als een byte‑array. |
| x | `float` | int x‑coördinaat van het bijlage‑frame (in punten). |
| y | `float` | int y‑coördinaat van het bijlage‑frame (in punten). |
| width | `float` | int breedte van het bijlage‑frame (in punten). |
| height | `float` | int hoogte van het bijlage‑frame (in punten). |

**Returns:** None.

### Voorbeeld

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
        # Integreer het bestand in het eerste werkblad, weergegeven als een voorbeeldafbeelding.
        # bij x=50, y=20 met een 100 x 120 frame
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Zie ook
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
