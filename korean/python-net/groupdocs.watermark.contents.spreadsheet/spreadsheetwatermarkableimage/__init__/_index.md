---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 이미지 데이터를 사용하여 SpreadsheetWatermarkableImage 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

지정된 이미지 데이터를 사용하여 [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, image_data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_data | `list[int]` | `SpreadsheetWatermarkableImage`를 생성할 때 사용할 부호 없는 바이트 배열. |

### 예시

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### 또 보기
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
