---
title: "get_row_height methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Retourneert de hoogte van de opgegeven rij in punten."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Retourneert de hoogte van de opgegeven rij in punten.

```python
def get_row_height(self, row):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| row | `int` | De rijindex. |

**Returns:** float: The height of the row in points.

### Voorbeeld

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

### Zie ook
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
