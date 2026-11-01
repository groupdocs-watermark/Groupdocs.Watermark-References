---
title: "get_document_info 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "첨부된 파일에 저장된 문서에 대한 정보를 검색합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

첨부된 파일에 저장된 문서에 대한 정보를 검색합니다.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### 또 보기
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
