---
title: or_ method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Combines this SearchCriteria with other criteria using logical OR operator."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Combines this SearchCriteria with other criteria using logical OR operator.

```python
def or_(self, other):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| other | `SearchCriteria` | Search criteria to combine with. |

**Returns:** SearchCriteria: Combined search criteria.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    image_criteria = gws_sc.ImageDctHashSearchCriteria("logo.png")
    text_criteria = gws_sc.TextSearchCriteria("Company Name")
    combined = image_criteria.or_(text_criteria)
    possible = watermarker.search(combined)
    print("Found", possible.count, "possible watermark(s)")
```

### See Also
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
