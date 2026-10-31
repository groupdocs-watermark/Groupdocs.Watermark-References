---
title: "فئة WordProcessingImageEffects"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل التأثيرات التي يمكن تطبيقها على علامة مائية صورة لمستند Word."
type: docs
url: /ar/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

يمثل التأثيرات التي يمكن تطبيقها على علامة مائية صورة لمستند Word.

نوع WordProcessingImageEffects يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | ينشئ مثيلاً جديداً من الفئة [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | إعدادات تنسيق الخط لإطار الصورة. (موروث من [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | سطوع الصورة. يجب أن يكون عددًا عشريًا بين 0.0 (أكثر تعتيمًا) و 1.0 (أكثر سطوعًا). القيمة الافتراضية هي 0.5. (موروث من [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | قيمة اللون في الصورة التي ستُعامل كشفافة. القيمة الافتراضية هي لون شفاف بالكامل. (موروث من [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | التباين للصورة المحددة. يجب أن يكون عددًا عشريًا بين 0.0 (أقل تباين) و 1.0 (أعلى تباين). القيمة الافتراضية هي 0.5. (موروث من [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | الخاصية تشير إلى ما إذا كانت الصورة ستُعرض بنمط التدرج الرمادي. (موروث من [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

### انظر أيضًا
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
