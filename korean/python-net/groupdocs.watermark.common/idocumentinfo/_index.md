---
title: "IDocumentInfo 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "기본 문서 정보를 검색하는 데 필요한 메서드를 제공합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

기본 문서 정보를 검색하는 데 필요한 메서드를 제공합니다.

자세히 알아보기: 문서 정보 가져오기.

IDocumentInfo 유형은 다음 멤버를 노출합니다:

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | 파일 형식 설명. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | 이 속성은 문서가 암호화되어 있으며 열기 위해 비밀번호가 필요한지 여부를 나타냅니다. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | 전체 페이지 수. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | 문서 페이지 설명의 컬렉션. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | 문서 크기(바이트). |

### 예시

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### 또 보기
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
