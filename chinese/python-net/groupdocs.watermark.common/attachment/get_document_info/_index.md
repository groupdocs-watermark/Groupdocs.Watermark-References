---
title: "get_document_info 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "检索存储在附件文件中的文档信息。"
type: docs
url: /zh/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

检索存储在附件文件中的文档信息。

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### 另请参见
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
