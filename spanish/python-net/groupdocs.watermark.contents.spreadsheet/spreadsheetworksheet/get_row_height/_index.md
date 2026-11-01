---
title: "get_row_height método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Devuelve la altura de la fila especificada en puntos."
type: docs
url: /es/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Devuelve la altura de la fila especificada en puntos.

```python
def get_row_height(self, row):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| row | `int` | El índice de fila. |

**Returns:** float: The height of the row in points.

### Ejemplo

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

### Ver también
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
