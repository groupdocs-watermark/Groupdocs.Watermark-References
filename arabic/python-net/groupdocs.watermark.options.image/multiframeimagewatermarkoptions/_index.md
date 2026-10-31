---
title: "فئة MultiframeImageWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة متعددة الإطارات."
type: docs
url: /ar/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة متعددة الإطارات.

المزيد: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

يعرض نوع MultiframeImageWatermarkOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | ينشئ مثيلًا جديدًا من الفئة [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | ينشئ مثيلًا جديدًا من الفئة [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) مع فهرس محدد للإطار. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | فهرس الإطار لإضافة علامة مائية. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### انظر أيضًا
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
