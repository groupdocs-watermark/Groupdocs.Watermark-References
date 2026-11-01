---
title: "get_column_width メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された列の幅（ポイント）を取得します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

指定された列の幅（ポイント）を取得します。

```python
def get_column_width(self, column):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| column | `int` | 列インデックスです。 |

**Returns:** float: The width of the column in points.

### 例

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

### 関連項目
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
