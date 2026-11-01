---
title: "SearchableObjects 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크 검색에 포함될 문서 객체를 지정합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

워터마크 검색에 포함될 문서 객체를 지정합니다.

자세히 알아보기:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SearchableObjects 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | 새로운 [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 클래스 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | 워터마크 검색에 포함될 Visio 문서 내부 객체입니다. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | 워터마크 검색에 포함될 이메일 메시지 내부 객체입니다. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | 워터마크 검색에 포함될 PDF 문서 내부 객체입니다. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | 워터마크 검색에 포함될 PowerPoint 문서 내부 객체입니다. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | 워터마크 검색에 포함될 Excel 문서 내부 객체입니다. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | 워터마크 검색에 포함될 Word 문서 내부 객체입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
`SearchableObjects`를 사용하는 작업 가이드:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 또 보기
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
