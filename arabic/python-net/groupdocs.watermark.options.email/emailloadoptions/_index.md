---
title: "فئة EmailLoadOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات تحميل المستند لرسالة بريد إلكتروني."
type: docs
url: /ar/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

يمثل خيارات تحميل المستند لرسالة بريد إلكتروني.

يعرض نوع EmailLoadOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | ينشئ مثيلاً جديدًا من الفئة [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | نوع الملف، موضحًا صيغته (مثل docx، pdf، xlsx، إلخ). (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | عائلة تنسيق المستند، موضحةً نوعه (مثل Image، Pdf، Spreadsheet، إلخ). (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | كلمة المرور لفتح مستند مشفر. (موروث من [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | يحصل على القيمة الافتراضية للفئة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # تعديل محتوى البريد الإلكتروني هنا
    watermarker.save("./output.msg")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
