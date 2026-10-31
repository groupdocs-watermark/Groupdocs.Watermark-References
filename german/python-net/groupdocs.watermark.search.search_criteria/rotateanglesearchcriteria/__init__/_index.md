---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert ein neues RotateAngleSearchCriteria mit einem Startwinkel und einem Endwinkel."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Initialisiert ein neues RotateAngleSearchCriteria mit einem Startwinkel und einem Endwinkel.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| min_angle | `float` | Der Startwinkel in Grad. |
| max_angle | `float` | Der Endwinkel in Grad. |

### Beispiel

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Suche nach Wasserzeichen, die zwischen 30 und 60 Grad gedreht sind
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Siehe auch
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
