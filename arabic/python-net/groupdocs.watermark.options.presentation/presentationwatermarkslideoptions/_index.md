---
title: "فئة PresentationWatermarkSlideOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل الخيارات عند إضافة علامة مائية إلى شريحة مستند عرض تقديمي."
type: docs
url: /ar/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
is_root: false
weight: 140
---


## PresentationWatermarkSlideOptions class

يمثل الخيارات عند إضافة علامة مائية إلى شريحة مستند عرض تقديمي.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

يعرض نوع PresentationWatermarkSlideOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/) | يُنشئ مثلاً جديدًا من الفئة [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/) . |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slide_index/) | فهرس الشريحة لإضافة العلامة المائية إليها. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | النص الوصفي (البديل) الذي سيتم ربطه بشكل. (موروث من [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | التأثيرات التي سيتم تطبيقها على العلامة المائية، محددة ككائن [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) أو [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) . (موروث من [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | الخاصية تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظوراً. (موروث من [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | اسم الشكل. (موروث من [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | الخاصية التي تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. (موروث من [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.presentation import (
    PresentationLoadOptions, PresentationWatermarkSlideOptions,
)

def add_watermark_to_slide():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = PresentationWatermarkSlideOptions()
        options.slide_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.pptx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
