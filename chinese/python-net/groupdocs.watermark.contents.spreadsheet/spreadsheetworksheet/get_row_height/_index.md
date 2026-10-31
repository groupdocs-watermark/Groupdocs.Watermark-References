---
title: "get_row_height 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "返回指定行的高度（单位：点）。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

返回指定行的高度（单位：点）。

```python
def get_row_height(self, row):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| row | `int` | 行索引。 |

**Returns:** float: The height of the row in points.

### 示例

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

### 另请参见
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
