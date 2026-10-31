---
title: "فئة PresentationWatermarkMasterSlideOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل الخيارات عند إضافة علامة مائية إلى الشريحة الرئيسية لمستند عرض تقديمي."
type: docs
url: /ar/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/
is_root: false
weight: 110
---


## PresentationWatermarkMasterSlideOptions class

يمثل الخيارات عند إضافة علامة مائية إلى الشريحة الرئيسية لمستند عرض تقديمي.

اعرف المزيد:
- [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

انظر أمثلة الاستخدام في [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

نوع PresentationWatermarkMasterSlideOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/__init__/) | ينشئ مثلاً جديداً من [`PresentationWatermarkMasterSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/) فئة. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [master_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/master_slide_index/) | فهرس الشريحة الرئيسية لإضافة العلامة المائية إليها. |
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
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt

watermarker = gw.Watermarker("presentation.pptx")
watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))

master_opts = gwo_ppt.PresentationWatermarkMasterSlideOptions()
master_opts.master_slide_index = -1
watermarker.add(watermark, master_opts)
```

### انظر أيضًا
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
