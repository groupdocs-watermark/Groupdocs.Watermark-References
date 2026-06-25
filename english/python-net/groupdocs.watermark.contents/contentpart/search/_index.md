---
title: search method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Finds possible watermarks according to the specified search criteria.

The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self, search_criteria):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | The search criteria to use. |

**Returns:** The collection of the possible watermarks.

## search

Finds all possible watermarks in the content. The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** The collection of the possible watermarks.

### See Also
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
