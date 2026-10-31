---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise un nouveau RotateAngleSearchCriteria avec un angle de départ et un angle de fin."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Initialise un nouveau RotateAngleSearchCriteria avec un angle de départ et un angle de fin.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| min_angle | `float` | L'angle de départ en degrés. |
| max_angle | `float` | L'angle de fin en degrés. |

### Exemple

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Rechercher les filigranes pivotés entre 30 et 60 degrés
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Voir aussi
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
