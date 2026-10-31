---
title: "فئة PdfLoadOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات تحميل المستند لمستند PDF."
type: docs
url: /ar/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/
is_root: false
weight: 30
---


## PdfLoadOptions class

يمثل خيارات تحميل المستند لمستند PDF.

يعرض نوع PdfLoadOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/) | ينشئ مثيلًا جديدًا للفئة [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/#password) | ينشئ مثيلًا جديدًا للفئة [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) باستخدام كلمة مرور محددة. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | نوع الملف، موضحًا صيغته (مثل docx، pdf، xlsx، إلخ). (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | عائلة تنسيق المستند، موضحةً نوعه (مثل Image، Pdf، Spreadsheet، إلخ). (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | كلمة المرور لفتح مستند مشفر. (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/default/) | يحصل على القيمة الافتراضية للفئة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    # تنفيذ عمليات على watermarker
    pass
```

### انظر أيضًا
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
