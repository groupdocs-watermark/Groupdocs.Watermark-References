---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa un nuevo RotateAngleSearchCriteria con un ángulo inicial y un ángulo final."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Inicializa un nuevo RotateAngleSearchCriteria con un ángulo inicial y un ángulo final.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| min_angle | `float` | El ángulo inicial en grados. |
| max_angle | `float` | El ángulo final en grados. |

### Ejemplo

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Buscar marcas de agua rotadas entre 30 y 60 grados
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Ver también
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
