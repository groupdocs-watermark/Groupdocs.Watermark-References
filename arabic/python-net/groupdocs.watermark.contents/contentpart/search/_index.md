---
title: "طريقة search"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | معايير البحث التي سيتم استخدامها. |

**Returns:** The collection of the possible watermarks.

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

يبحث عن جميع العلامات المائية المحتملة في المحتوى.

يتم إجراء البحث في الكائنات المحددة في [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### انظر أيضًا
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
