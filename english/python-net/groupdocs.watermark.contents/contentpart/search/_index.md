---
title: search method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Finds possible watermarks according to the specified search criteria."
type: docs
url: /python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Finds possible watermarks according to the specified search criteria. The search is performed on the objects listed in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | The search criteria to use. |

**Returns:** The collection of the possible watermarks.

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Finds all possible watermarks in the content.

The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### See Also
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
