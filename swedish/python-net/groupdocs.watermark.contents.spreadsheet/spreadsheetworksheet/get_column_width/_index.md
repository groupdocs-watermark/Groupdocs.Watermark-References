---
title: "get_column_width metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hämtar bredden på den angivna kolumnen i punkter."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Hämtar bredden på den angivna kolumnen i punkter.

```python
def get_column_width(self, column):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| column | `int` | Kolumnindexet. |

**Returns:** float: The width of the column in points.

### Exempel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    width = content.worksheets[0].get_column_width(0)
    print(width)
```

### Se även
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
