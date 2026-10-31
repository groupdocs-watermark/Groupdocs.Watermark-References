---
title: "metodo get_document_info"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Recupera le informazioni su un documento memorizzato nel file allegato."
type: docs
url: /it/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Recupera le informazioni su un documento memorizzato nel file allegato.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Vedi anche
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
