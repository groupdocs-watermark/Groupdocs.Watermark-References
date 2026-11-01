---
title: "get_document_info-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Haalt de informatie op over een document dat is opgeslagen in het bijgevoegde bestand."
type: docs
url: /nl/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Haalt de informatie op over een document dat is opgeslagen in het bijgevoegde bestand.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Zie ook
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
