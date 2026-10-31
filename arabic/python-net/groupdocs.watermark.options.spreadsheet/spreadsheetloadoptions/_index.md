---
title: "فئة SpreadsheetLoadOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات تحميل المستند لمستند Spreadsheet."
type: docs
url: /ar/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

يمثل خيارات تحميل المستند لمستند Spreadsheet.

يعرض نوع SpreadsheetLoadOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | ينشئ مثلاً جديداً من الفئة [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | ينشئ مثلاً جديداً من الفئة [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) مع كلمة مرور محددة. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | نوع الملف، موضحًا صيغته (مثل docx، pdf، xlsx، إلخ). (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | عائلة تنسيق المستند، موضحةً نوعه (مثل Image، Pdf، Spreadsheet، إلخ). (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | كلمة المرور لفتح مستند مشفر. (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | يحصل على القيمة الافتراضية للفئة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # نفّذ عمليات العلامة المائية هنا
    pass
```

### انظر أيضًا
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
