---
title: "فئة SpreadsheetTextEffects"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل التأثيرات التي يمكن تطبيقها على علامة مائية نصية لمستند Excel."
type: docs
url: /ar/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/
is_root: false
weight: 80
---


## SpreadsheetTextEffects class

يمثل التأثيرات التي يمكن تطبيقها على علامة مائية نصية لمستند Excel.

يعرض نوع SpreadsheetTextEffects الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/) | ينشئ مثلاً جديداً من الفئة [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | إعدادات تنسيق الخط، ممثلة بواسطة مثيل [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (موروثة من [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Segoe UI", 19.0))
    effects = gwo_xls.SpreadsheetTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1
    options = gwo_xls.SpreadsheetWatermarkShapeOptions()
    options.effects = effects
    watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
