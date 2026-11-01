---
title: "get_document_info 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "로드된 문서 형식에 대한 정보를 가져옵니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

로드된 문서 형식에 대한 정보를 가져옵니다.

문서 정보를 가져오는 방법에 대해 자세히 알아보세요

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### 예시

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
