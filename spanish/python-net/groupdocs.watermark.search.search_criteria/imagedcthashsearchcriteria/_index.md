---
title: "Clase ImageDctHashSearchCriteria"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un criterio de búsqueda para encontrar imágenes en un documento."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

Representa un criterio de búsqueda para encontrar imágenes en un documento.

Este criterio de búsqueda utiliza un hash de imagen perceptual basado en DCT para calcular la similitud de imágenes. Obtenga más información: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

El tipo ImageDctHashSearchCriteria expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | Inicializa una nueva instancia de ImageDctHashSearchCriteria con una ruta de archivo especificada. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | Inicializa una nueva instancia de ImageDctHashSearchCriteria con el flujo de imagen proporcionado. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | La diferencia máxima permitida entre imágenes. (heredado de [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | La lista de números de página específicos. (heredado de [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
Guías de tareas que usan `ImageDctHashSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
