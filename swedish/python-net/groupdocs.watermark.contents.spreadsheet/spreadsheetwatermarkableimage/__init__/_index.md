---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen SpreadsheetWatermarkableImage med angivna bilddata."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initierar en ny instans av klassen [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) med angivna bilddata.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_data | `list[int]` | Arrayen av osignerade byte från vilka `SpreadsheetWatermarkableImage` ska skapas. |

### Exempel

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Se även
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
