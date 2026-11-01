---
title: "Clase SizeSearchCriteria"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa criterios que permiten filtrar por tamaño de la marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

Representa criterios que permiten filtrar por tamaño de la marca de agua.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

El tipo SizeSearchCriteria expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | Inicializa una nueva instancia de la clase SizeSearchCriteria con una dimensión especificada, un valor inicial y un valor final. |

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
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | La dimensión de la marca de agua por la que buscar. |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | El valor final. |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | El valor inicial. |

### Ejemplo

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.common import Dimension
from groupdocs.watermark.search.search_criteria import SizeSearchCriteria, RotateAngleSearchCriteria, TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    width_range = SizeSearchCriteria(Dimension.WIDTH, 50, 100)
    rotate_angle = RotateAngleSearchCriteria(0, 45)
    text_criteria = TextSearchCriteria(re.compile(r"^Test watermark$"))
    watermarks = watermarker.search(text_criteria.and_(width_range.or_(rotate_angle)))
    watermarks.clear()
    watermarker.save("./output.pdf")
```

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
