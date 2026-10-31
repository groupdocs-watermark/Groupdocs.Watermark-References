---
title: "get_document_info méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Récupère les informations sur un document stocké dans le fichier joint."
type: docs
url: /fr/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Récupère les informations sur un document stocké dans le fichier joint.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Voir aussi
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
