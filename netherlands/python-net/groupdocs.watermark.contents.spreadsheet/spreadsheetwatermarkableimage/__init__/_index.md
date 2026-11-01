---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de SpreadsheetWatermarkableImage‑klasse met opgegeven afbeeldingsgegevens."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialiseert een nieuw exemplaar van de [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) klasse met gespecificeerde afbeeldingsgegevens.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_data | `list[int]` | De array van ongetekende bytes waaruit de `SpreadsheetWatermarkableImage` wordt gemaakt. |

### Voorbeeld

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Zie ook
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
