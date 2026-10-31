---
title: "طريقة get_document_info"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يسترجع المعلومات حول المستند المخزن في الملف المرفق."
type: docs
url: /ar/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

يسترجع المعلومات حول المستند المخزن في الملف المرفق.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### انظر أيضًا
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
