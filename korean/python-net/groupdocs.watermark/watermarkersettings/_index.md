---
title: "WatermarkerSettings 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "Watermarker 동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Watermarker 동작을 사용자 정의하기 위한 설정을 정의합니다.

WatermarkerSettings 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | WatermarkerSettings의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | 워터마크 처리 중 이벤트와 오류를 기록하는 데 사용되는 로거입니다. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | 워터마크 검색에 포함될 검색 가능한 객체들입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | 클래스의 기본값을 가져옵니다. |

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
`WatermarkerSettings`를 사용하는 작업 가이드:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 또 보기
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
