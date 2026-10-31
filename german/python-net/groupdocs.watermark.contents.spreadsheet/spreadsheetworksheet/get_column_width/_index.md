---
title: "get_column_width Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Ermittelt die Breite der angegebenen Spalte in Punkten."
type: docs
url: /de/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Ermittelt die Breite der angegebenen Spalte in Punkten.

```python
def get_column_width(self, column):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| column | `int` | Der Spaltenindex. |

**Returns:** float: The width of the column in points.

### Beispiel

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

### Siehe auch
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
