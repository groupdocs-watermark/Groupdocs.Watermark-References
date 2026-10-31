---
title: "طريقة search"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يبحث عن جميع العلامات المائية الممكنة في المستند."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

يبحث عن جميع العلامات المائية الممكنة في المستند.

يتم إجراء البحث في الكائنات المحددة في [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

تعرف على المزيد حول البحث عن العلامات المائية https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### مثال

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

يبحث عن العلامات المائية الممكنة وفقًا لمعايير البحث المحددة.

يتم إجراء البحث في الكائنات المحددة في [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

تعرف على المزيد حول البحث عن العلامات المائية: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | معايير البحث التي سيتم استخدامها. |

**Returns:** The collection of possible watermarks.

### مثال

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

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
