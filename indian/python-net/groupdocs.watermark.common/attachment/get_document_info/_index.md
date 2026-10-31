---
title: "get_document_info मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "संलग्न फ़ाइल में संग्रहीत दस्तावेज़ की जानकारी प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

संलग्न फ़ाइल में संग्रहीत दस्तावेज़ की जानकारी प्राप्त करता है।

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### संबंधित देखें
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
