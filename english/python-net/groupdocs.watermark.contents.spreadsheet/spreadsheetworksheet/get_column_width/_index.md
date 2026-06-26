---
title: get_column_width method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Returns the width of the specified column in points."
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Returns the width of the specified column in points.

```python
def get_column_width(self, column):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| column | `int` | The column index. |

**Returns:** float: The width of the column in points.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = gw.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content(gwc_xls.SpreadsheetContent)
    width = content.worksheets[0].get_column_width(0)
    print(width)
```

### See Also
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
