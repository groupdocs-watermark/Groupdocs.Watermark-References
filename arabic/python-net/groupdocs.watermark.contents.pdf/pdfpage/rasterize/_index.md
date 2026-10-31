---
title: "طريقة rasterize"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بتحويل محتوى الصفحة إلى صورة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

يقوم بتحويل محتوى الصفحة إلى صورة.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| horizontal_resolution | `int` | دقة الصورة الأفقية. |
| vertical_resolution | `int` | دقة الصورة العمودية. |
| image_format | `PdfImageConversionFormat` | تنسيق الصورة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # تحويل الصفحة الأولى إلى صورة PNG بدقة 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### انظر أيضًا
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
