---
title: get_row_height method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Returns the height of the specified row in points."
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Returns the height of the specified row in points.

```python
def get_row_height(self, row):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| row | `int` | The row index. |

**Returns:** float: The height of the row in points.

### Example

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.spreadsheet as gwc_xls

    load_options = gw.SpreadsheetLoadOptions()
    with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
        content = watermarker.get_content(gwc_xls.SpreadsheetContent)
        height = content.worksheets[0].get_row_height(0)
        print(height)
    ```

### See Also
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
