---
title: "فئة Attachment"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل ملفًا مرفقًا بوثيقة."
type: docs
url: /ar/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

يمثل ملفًا مرفقًا بوثيقة.

تعرف على المزيد

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

نوع Attachment يعرض الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | يقوم بتحميل محتوى من الملف المرفق. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل المحددة. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل والإعدادات المحددة. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | يسترجع المعلومات حول المستند المخزن في الملف المرفق. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | محتوى الملف المرفق. |

### مثال

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))
load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("output.pdf")
```

### انظر أيضًا
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
