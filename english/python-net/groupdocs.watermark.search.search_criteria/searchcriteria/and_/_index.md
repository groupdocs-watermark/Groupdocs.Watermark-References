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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Combine criteria: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### See Also
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
