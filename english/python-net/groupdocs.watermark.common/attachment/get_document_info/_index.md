---
title: get_document_info method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Retrieves the information about a document stored in the attached file."
type: docs
url: /python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Retrieves the information about a document stored in the attached file.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### See Also
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
