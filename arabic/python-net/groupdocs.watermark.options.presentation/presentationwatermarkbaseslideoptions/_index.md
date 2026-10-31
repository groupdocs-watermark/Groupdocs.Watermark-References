---
title: "فئة PresentationWatermarkBaseSlideOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند عرض تقديمي."
type: docs
url: /ar/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند عرض تقديمي.

اعرف المزيد:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

يعرض نوع PresentationWatermarkBaseSlideOptions الأعضاء التالية:

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | النص الوصفي (البديل) الذي سيتم ربطه بالشكل. |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | التأثيرات التي تُطبق على العلامة المائية، محددة ككائن [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) أو [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | تشير الخاصية إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا. |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | اسم الشكل. |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | الخاصية التي تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
