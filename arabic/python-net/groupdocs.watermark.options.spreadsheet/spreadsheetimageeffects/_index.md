---
title: "فئة SpreadsheetImageEffects"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل التأثيرات التي يمكن تطبيقها على علامة مائية صورة لمستند Excel."
type: docs
url: /ar/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

يمثل التأثيرات التي يمكن تطبيقها على علامة مائية صورة لمستند Excel.

يعرض نوع SpreadsheetImageEffects الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | ينشئ مثلاً جديداً من الفئة [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/). |

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
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_xls.SpreadsheetImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1
        options = gwo_xls.SpreadsheetWatermarkShapeOptions()
        options.effects = effects
        watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
