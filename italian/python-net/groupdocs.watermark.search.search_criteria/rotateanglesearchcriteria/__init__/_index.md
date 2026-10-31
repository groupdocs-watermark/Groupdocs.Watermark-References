---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza un nuovo RotateAngleSearchCriteria con un angolo iniziale e un angolo finale."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Inizializza un nuovo RotateAngleSearchCriteria con un angolo iniziale e un angolo finale.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| min_angle | `float` | L'angolo iniziale in gradi. |
| max_angle | `float` | L'angolo finale in gradi. |

### Esempio

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Cerca filigrane ruotate tra 30 e 60 gradi
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Vedi anche
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
