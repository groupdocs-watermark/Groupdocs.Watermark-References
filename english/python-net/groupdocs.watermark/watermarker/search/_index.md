---
title: search method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Searches all possible watermarks in the document.

The search is conducted in objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Learn more about searching watermarks: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

```python
def search(self):
    ...
```

**Returns:** PossibleWatermarkCollection: The collection of possible watermarks.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    text_criteria = gws_sc.TextSearchCriteria("© 2017")
    possible = watermarker.search(text_criteria)
    print("Found", possible.count, "possible watermark(s)")
```

## search {#search_criteria}

Searches possible watermarks according to specified search criteria.

The search is conducted in objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Learn more about searching watermarks: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

```python
def search(self, search_criteria):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | The search criteria to use. |

**Returns:** The collection of possible watermarks.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    text_criteria = gws_sc.TextSearchCriteria("© 2017")
    possible = watermarker.search(text_criteria)
    print("Found", possible.count, "possible watermark(s)")
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
