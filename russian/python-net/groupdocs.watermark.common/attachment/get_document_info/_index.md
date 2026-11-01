---
title: "метод get_document_info"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Получает информацию о документе, хранящемся в прикреплённом файле."
type: docs
url: /ru/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Получает информацию о документе, хранящемся в прикреплённом файле.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### См. также
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
