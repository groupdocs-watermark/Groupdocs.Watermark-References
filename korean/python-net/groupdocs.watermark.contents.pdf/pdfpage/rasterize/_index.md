---
title: "rasterize 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "페이지 콘텐츠를 이미지로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

페이지 콘텐츠를 이미지로 변환합니다.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # 첫 페이지를 100 DPI로 PNG 이미지로 래스터화
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### 또 보기
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
