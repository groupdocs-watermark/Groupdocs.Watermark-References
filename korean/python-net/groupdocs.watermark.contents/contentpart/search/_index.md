---
title: "search 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 검색 기준에 따라 가능한 워터마크를 찾습니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다.

```python
def search(self, search_criteria):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | 사용할 검색 기준. |

**Returns:** The collection of the possible watermarks.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

콘텐츠 내 모든 가능한 워터마크를 찾습니다.

검색은 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/)에 지정된 객체에서 수행됩니다.

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### 또 보기
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
