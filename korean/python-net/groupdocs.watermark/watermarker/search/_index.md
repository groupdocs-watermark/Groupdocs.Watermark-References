---
title: "search 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서에서 가능한 모든 워터마크를 검색합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

문서에서 가능한 모든 워터마크를 검색합니다.

검색은 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/)에 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보려면 https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

## search {#search_criteria}

지정된 검색 기준에 따라 가능한 워터마크를 검색합니다.

검색은 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/)에 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보려면: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | 사용할 검색 기준. |

**Returns:** The collection of possible watermarks.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
