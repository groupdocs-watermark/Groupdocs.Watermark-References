---
title: "metodo get_column_width"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Restituisce la larghezza della colonna specificata in punti."
type: docs
url: /it/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Restituisce la larghezza della colonna specificata in punti.

```python
def get_column_width(self, column):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| column | `int` | L'indice della colonna. |

**Returns:** float: The width of the column in points.

### Esempio

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

### Vedi anche
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
