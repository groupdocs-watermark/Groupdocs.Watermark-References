---
title: "get_document_info-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Ruft die Informationen über ein im angehängten Datei gespeichertes Dokument ab."
type: docs
url: /de/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Ruft die Informationen über ein im angehängten Datei gespeichertes Dokument ab.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Siehe auch
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
