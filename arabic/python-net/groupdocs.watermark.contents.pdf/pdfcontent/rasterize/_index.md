---
title: "طريقة rasterize"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحوّل جميع صفحات المحتوى إلى صور."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

يحوّل جميع صفحات المحتوى إلى صور.

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
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # إضافة علامة مائية (اختياري)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # تحويل كل صفحة إلى نقطية بدقة 100×100 DPI إلى صور PNG
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### انظر أيضًا
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
