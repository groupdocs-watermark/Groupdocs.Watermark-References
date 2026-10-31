---
title: "get_document_info metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengambil informasi tentang dokumen yang disimpan dalam file yang dilampirkan."
type: docs
url: /id/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Mengambil informasi tentang dokumen yang disimpan dalam file yang dilampirkan.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Lihat Juga
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
