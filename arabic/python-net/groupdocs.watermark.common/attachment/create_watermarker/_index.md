---
title: "طريقة create_watermarker"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بتحميل محتوى من الملف المرفق."
type: docs
url: /ar/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

يقوم بتحميل محتوى من الملف المرفق.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### مثال

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content()
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل المحددة.

```python
def create_watermarker(self, load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| load_options | `LoadOptions` | خيارات إضافية لاستخدامها عند تحميل محتوى المرفق. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل والإعدادات المحددة.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| load_options | `LoadOptions` | خيارات إضافية لاستخدامها عند تحميل محتوى المرفق. |
| watermarker_settings | `WatermarkerSettings` | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

**Returns:** The instance of appropriate descendant of `Content` class.

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("output.pdf")
```

### انظر أيضًا
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
