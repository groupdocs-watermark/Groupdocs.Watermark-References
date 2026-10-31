---
title: "metodo get_row_height"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Restituisce l'altezza della riga specificata in punti."
type: docs
url: /it/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Restituisce l'altezza della riga specificata in punti.

```python
def get_row_height(self, row):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| row | `int` | L'indice della riga. |

**Returns:** float: The height of the row in points.

### Esempio

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

### Vedi anche
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
