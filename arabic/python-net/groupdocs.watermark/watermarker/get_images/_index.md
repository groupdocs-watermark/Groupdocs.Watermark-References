---
title: "طريقة get_images"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يجد الصور وفقًا لمعايير البحث المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

يجد الصور وفقًا لمعايير البحث المحددة.

يتم إجراء البحث في الكائنات المحددة في [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

تعرف على المزيد حول البحث عن العلامات المائية https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | معايير البحث التي سيتم استخدامها. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType

with Watermarker("./document.pdf") as watermarker:
    watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
    watermark.foreground_color = Color.red
    watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS

    for image in watermarker.get_images():
        if image.width > 100 and image.height > 100:
            image.add(watermark)

    watermarker.save("./output.pdf")
```

## get_images

يجد جميع الصور في المستند.

يتم إجراء البحث في الكائنات المحددة في [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

تعرف على المزيد حول البحث عن العلامات المائية على https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # كل صورة نقطية مدمجة في المستند
        for image in watermarker.get_images():
            # تخطي الصور الصغيرة مثل الأيقونات أو النقاط
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
