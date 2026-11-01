---
title: "get_column_width methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Haalt de breedte van de opgegeven kolom op in punten."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Haalt de breedte van de opgegeven kolom op in punten.

```python
def get_column_width(self, column):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| column | `int` | De kolomindex. |

**Returns:** float: The width of the column in points.

### Voorbeeld

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

### Zie ook
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
