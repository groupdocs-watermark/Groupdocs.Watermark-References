---
title: "méthode get_column_width"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Obtient la largeur de la colonne spécifiée en points."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Obtient la largeur de la colonne spécifiée en points.

```python
def get_column_width(self, column):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| column | `int` | L'index de colonne. |

**Returns:** float: The width of the column in points.

### Exemple

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

### Voir aussi
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
