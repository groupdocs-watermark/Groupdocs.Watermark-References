---
title: "Clase VectorSearchCriteria"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa criterios que permiten filtrar por color de la marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

Representa criterios que permiten filtrar por color de la marca de agua.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

El tipo VectorSearchCriteria expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Inicializa una nueva instancia de [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/). |

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
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | El rango de colores usado para filtrar marcas de agua vectoriales por color de primer plano. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import VectorSearchCriteria, ColorRange
from groupdocs.watermark.watermarks import Color

with Watermarker("./document.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = Color.from_argb(255, 169, 170, 174)  # #a9aaae
    color_range = ColorRange(watermark_color)
    color_range.min_brightness = 0.1
    color_range.max_brightness = 0.7
    search_criteria.vector_color_range = color_range

    possible_watermarks = watermarker.search(search_criteria)
    possible_watermarks.clear()
    watermarker.save("./output.pdf")
```

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
