---
title: "فئة WordProcessingWatermarkBaseOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Word."
type: docs
url: /ar/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/
is_root: false
weight: 90
---


## WordProcessingWatermarkBaseOptions class

يمثل الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Word.

يعرض نوع WordProcessingWatermarkBaseOptions الأعضاء التالية:

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | النص الوصفي (البديل) الذي سيتم ربطه بالشكل. |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | التأثيرات التي تُطبق على العلامة المائية، محددة ككائن [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) أو [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | تشير الخاصية إلى ما إذا كان تحرير الشكل في Word محظورًا. |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | نوع قفل العلامة المائية. |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | اسم الشكل. |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | كلمة المرور المستخدمة لقفل العلامة المائية. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.options.word_processing import WordProcessingWatermarkSectionOptions, WordProcessingLockType
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected", Font("Arial", 36.0))
    options = WordProcessingWatermarkSectionOptions()
    options.is_locked = True
    options.lock_type = WordProcessingLockType.ALLOW_ONLY_FORM_FIELDS
    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
