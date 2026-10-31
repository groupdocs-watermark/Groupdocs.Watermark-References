---
title: "get_column_width 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "获取指定列的宽度（单位：点）。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

获取指定列的宽度（单位：点）。

```python
def get_column_width(self, column):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| column | `int` | 列索引。 |

**Returns:** float: The width of the column in points.

### 示例

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

### 另请参见
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
