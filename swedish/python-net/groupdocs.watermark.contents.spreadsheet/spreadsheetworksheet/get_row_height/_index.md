---
title: "get_row_height metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Returnerar höjden på den angivna raden i punkter."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Returnerar höjden på den angivna raden i punkter.

```python
def get_row_height(self, row):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| row | `int` | Radindexet. |

**Returns:** float: The height of the row in points.

### Exempel

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

### Se även
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
