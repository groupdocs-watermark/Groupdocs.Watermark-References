---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny RotateAngleSearchCriteria med en startvinkel och en slutvinkel."
type: docs
url: /sv/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Initierar en ny RotateAngleSearchCriteria med en startvinkel och en slutvinkel.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| min_angle | `float` | Startvinkeln i grader. |
| max_angle | `float` | Slutvinkeln i grader. |

### Exempel

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Sök efter vattenstämplar roterade mellan 30 och 60 grader
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Se även
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
