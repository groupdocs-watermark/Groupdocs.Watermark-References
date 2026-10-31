---
title: "فئة SpreadsheetBackgroundWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل الخيارات عند إضافة العلامة المائية كخلفية إلى ورقة عمل Spreadsheet."
type: docs
url: /ar/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

يمثل الخيارات عند إضافة العلامة المائية كخلفية إلى ورقة عمل Spreadsheet.

المزيد: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

يعرض نوع SpreadsheetBackgroundWatermarkOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | ينشئ مثلاً جديداً من الفئة [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | الارتفاع المطلوب لصورة الخلفية بالبكسل. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | العرض المطلوب لصورة الخلفية بالبكسل. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | فهرس ورقة العمل التي سيتم إضافة العلامة المائية إليها. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetBackgroundWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker(r"C:\Documents\test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36))

    options = SpreadsheetBackgroundWatermarkOptions()
    options.worksheet_index = -1  # default
    options.background_width = 800
    options.background_height = 600

    watermarker.add(watermark, options)
    watermarker.save()
```

### انظر أيضًا
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
