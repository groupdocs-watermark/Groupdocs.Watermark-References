---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new RotateAngleSearchCriteria with a starting angle and an ending angle."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Initializes a new RotateAngleSearchCriteria with a starting angle and an ending angle.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| min_angle | `float` | The starting angle in degrees. |
| max_angle | `float` | The ending angle in degrees. |

### Example

```python
from groupdocs.watermark.search import searchcriteria as gws_sc

# Search for watermarks rotated between 30 and 60 degrees
angle_criteria = gws_sc.RotateAngleSearchCriteria(30, 60)
```

### See Also
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
