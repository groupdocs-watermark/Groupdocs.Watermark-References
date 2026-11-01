---
title: "get_document_info メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "添付ファイルに保存されているドキュメントに関する情報を取得します。"
type: docs
url: /ja/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

添付ファイルに保存されているドキュメントに関する情報を取得します。

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### 関連項目
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
