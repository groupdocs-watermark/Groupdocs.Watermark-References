---
title: "get_row_height 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 행의 높이를 포인트 단위로 반환합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

지정된 행의 높이를 포인트 단위로 반환합니다.

```python
def get_row_height(self, row):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| row | `int` | 행 인덱스. |

**Returns:** float: The height of the row in points.

### 예시

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

### 또 보기
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
