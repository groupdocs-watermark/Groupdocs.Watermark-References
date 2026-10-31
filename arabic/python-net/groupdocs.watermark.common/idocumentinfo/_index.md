---
title: "فئة IDocumentInfo"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يوفر الطرق المطلوبة لاسترجاع معلومات الوثيقة الأساسية."
type: docs
url: /ar/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

يوفر الطرق المطلوبة لاسترجاع معلومات الوثيقة الأساسية.

اعرف المزيد: احصل على معلومات المستند.

يعرض نوع IDocumentInfo الأعضاء التالية:

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | وصف تنسيق الملف. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | تشير الخاصية إلى ما إذا كان المستند مشفراً ويتطلب كلمة مرور للفتح. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | إجمالي عدد الصفحات. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | مجموعة أوصاف صفحات المستند. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | حجم المستند بالبايت. |

### مثال

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### انظر أيضًا
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
