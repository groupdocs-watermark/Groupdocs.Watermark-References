---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 이미지 데이터를 사용하여 PdfWatermarkableImage 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

지정된 이미지 데이터를 사용하여 [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, image_data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_data | `list[int]` | `PdfWatermarkableImage`를 생성하기 위한 부호 없는 바이트 배열입니다. |

### 예시

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### 또 보기
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
