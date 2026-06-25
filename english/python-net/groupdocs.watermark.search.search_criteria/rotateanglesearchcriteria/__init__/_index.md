---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Initializes a new instance of the RotateAngleSearchCriteria class with a starting angle and an ending angle.

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
import groupdocs.watermark.search.searchcriteria as gws_sc

angle_criteria = gws_sc.RotateAngleSearchCriteria(30, 60)
```

### See Also
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
