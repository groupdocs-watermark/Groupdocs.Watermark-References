---
title: "rasterize 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "모든 콘텐츠 페이지를 이미지로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

모든 콘텐츠 페이지를 이미지로 변환합니다.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| horizontal_resolution | `int` | 수평 이미지 해상도. |
| vertical_resolution | `int` | 수직 이미지 해상도. |
| image_format | `PdfImageConversionFormat` | 이미지 형식. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # 워터마크 추가 (옵션)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # 모든 페이지를 100x100 DPI로 래스터화하여 PNG 이미지로 변환
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### 또 보기
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
