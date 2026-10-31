---
title: "méthode get_row_height"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Renvoie la hauteur de la ligne spécifiée en points."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Renvoie la hauteur de la ligne spécifiée en points.

```python
def get_row_height(self, row):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| row | `int` | L'index de ligne. |

**Returns:** float: The height of the row in points.

### Exemple

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
    import groupdocs.watermark.contents.spreadsheet as gwc_xls

    load_options = SpreadsheetLoadOptions()
    with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
        content = watermarker.get_content()
        height = content.worksheets[0].get_row_height(0)
        print(height)
    ```

### Voir aussi
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
