---
title: and_ method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Combines this SearchCriteria with other criteria using the logical AND operator."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Combines this SearchCriteria with other criteria using the logical AND operator.

```python
def and_(self, other):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| other | `SearchCriteria` | Search criteria to combine with. |

**Returns:** Combined search criteria.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    image_criteria = gws_sc.ImageDctHashSearchCriteria("logo.png")
    image_criteria.max_difference = 0.9
    text_criteria = gws_sc.TextSearchCriteria("Company Name")
    angle_criteria = gws_sc.RotateAngleSearchCriteria(30, 60)

    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    possible = watermarker.search(combined)
    print("Found", possible.count, "possible watermark(s)")
```

### See Also
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
