---
title: "get_document_info yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Ekli dosyada depolanan bir belge hakkında bilgileri alır."
type: docs
url: /tr/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Ekli dosyada depolanan bir belge hakkında bilgileri alır.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Ayrıca Bakınız
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
