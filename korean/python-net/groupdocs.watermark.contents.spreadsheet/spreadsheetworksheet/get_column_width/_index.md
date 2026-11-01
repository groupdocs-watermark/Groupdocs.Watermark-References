---
title: "get_column_width 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 열의 너비를 포인트 단위로 가져옵니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

지정된 열의 너비를 포인트 단위로 가져옵니다.

```python
def get_column_width(self, column):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| column | `int` | 열 인덱스. |

**Returns:** float: The width of the column in points.

### 예시

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

### 또 보기
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
