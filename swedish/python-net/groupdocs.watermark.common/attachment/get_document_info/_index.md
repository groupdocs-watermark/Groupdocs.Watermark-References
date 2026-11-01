---
title: "get_document_info-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hämtar information om ett dokument som lagras i den bifogade filen."
type: docs
url: /sv/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Hämtar information om ett dokument som lagras i den bifogade filen.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Se även
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
