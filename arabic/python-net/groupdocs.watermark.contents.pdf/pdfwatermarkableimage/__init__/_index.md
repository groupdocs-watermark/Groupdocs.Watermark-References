---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديداً من الفئة PdfWatermarkableImage باستخدام بيانات الصورة المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

يُنشئ مثلاً جديداً من الفئة [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) باستخدام بيانات الصورة المحددة.

```python
def __init__(self, image_data):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_data | `list[int]` | المصفوفة من البايتات غير الموقعة التي تُنشأ منها `PdfWatermarkableImage`. |

### مثال

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### انظر أيضًا
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
