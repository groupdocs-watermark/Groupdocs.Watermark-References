---
title: "طريقة get_column_width"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحصل على عرض العمود المحدد بالنقاط."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

يحصل على عرض العمود المحدد بالنقاط.

```python
def get_column_width(self, column):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| column | `int` | مؤشر العمود. |

**Returns:** float: The width of the column in points.

### مثال

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

### انظر أيضًا
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
