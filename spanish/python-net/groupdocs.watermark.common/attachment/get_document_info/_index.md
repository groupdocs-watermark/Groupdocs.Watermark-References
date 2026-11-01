---
title: "método get_document_info"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Recupera la información sobre un documento almacenado en el archivo adjunto."
type: docs
url: /es/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Recupera la información sobre un documento almacenado en el archivo adjunto.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Ver también
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
