---
title: "فئة WordProcessingTextEffects"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل التأثيرات التي يمكن تطبيقها على علامة مائية نصية لمستند Word."
type: docs
url: /ar/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/
is_root: false
weight: 80
---


## WordProcessingTextEffects class

يمثل التأثيرات التي يمكن تطبيقها على علامة مائية نصية لمستند Word.

نوع WordProcessingTextEffects يكشف عن الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/__init__/) | ينشئ مثلاً جديداً من الفئة [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [flip_orientation](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/flip_orientation/) | اتجاه الشكل. |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | إعدادات تنسيق الخط، ممثلة بواسطة مثيل [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (موروثة من [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/default/) | يحصل على القيمة الافتراضية للفئة. |

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.word_processing as gwo_wp
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_wp.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))

    effects = gwo_wp.WordProcessingTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1

    options = gwo_wp.WordProcessingWatermarkSectionOptions()
    options.effects = effects

    watermarker.add(watermark, options)
    watermarker.save("output.docx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
