---
title: "get_column_width método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Obtiene el ancho de la columna especificada en puntos."
type: docs
url: /es/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Obtiene el ancho de la columna especificada en puntos.

```python
def get_column_width(self, column):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| column | `int` | El índice de columna. |

**Returns:** float: The width of the column in points.

### Ejemplo

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

### Ver también
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
