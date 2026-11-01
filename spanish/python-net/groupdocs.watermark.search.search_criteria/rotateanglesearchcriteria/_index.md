---
title: "Clase RotateAngleSearchCriteria"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa criterios que permiten filtrar por ángulo de rotación de la marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

Representa criterios que permiten filtrar por ángulo de rotación de la marca de agua.

Aprende más:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

El tipo RotateAngleSearchCriteria expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | Inicializa un nuevo RotateAngleSearchCriteria con un ángulo inicial y un ángulo final. |

### Métodos
| Método | Descripción |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combina este SearchCriteria con otros criterios usando el operador lógico AND. (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Niega este SearchCriteria. (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combina este SearchCriteria con otros criterios usando el operador lógico OR. (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | El ángulo final en grados. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | El ángulo inicial en grados. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
Guías de tareas que usan `RotateAngleSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
