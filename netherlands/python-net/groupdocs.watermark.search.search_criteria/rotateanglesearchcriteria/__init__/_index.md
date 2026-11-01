---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe RotateAngleSearchCriteria met een starthoek en een eindhoek."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Initialiseert een nieuwe RotateAngleSearchCriteria met een starthoek en een eindhoek.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| min_angle | `float` | De starthoek in graden. |
| max_angle | `float` | De eindhoek in graden. |

### Voorbeeld

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Zoek naar watermerken gedraaid tussen 30 en 60 graden
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Zie ook
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
