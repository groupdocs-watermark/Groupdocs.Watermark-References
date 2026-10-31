---
title: "فئة GifImageWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى ملف GIF."
type: docs
url: /ar/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
is_root: false
weight: 30
---


## GifImageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى ملف GIF.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

نوع GifImageWatermarkOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/) | ينشئ مثيلاً جديدًا من الفئة [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/#frame_index) | ينشئ مثيلاً جديدًا من الفئة [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) مع فهرس إطار محدد. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | فهرس الإطار لإضافة علامة مائية. (موروث من [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import GifImageLoadOptions, GifImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = GifImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))

    options = GifImageWatermarkOptions()
    options.frame_index = 0

    watermarker.add(watermark, options)
    watermarker.save()
```

### انظر أيضًا
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
