---
title: "Clase TextSearchCriteria"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa criterios que permiten filtrar por texto de la marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

Representa criterios que permiten filtrar por texto de la marca de agua.

Aprende más:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

El tipo TextSearchCriteria expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | Inicializa un nuevo TextSearchCriteria con una expresión regular especificada. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | Inicializa una nueva instancia de la clase [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una cadena de búsqueda y una bandera para comparación sensible a mayúsculas. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | Inicializa una nueva instancia de la clase [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una cadena de búsqueda. |

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
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | El patrón de expresión regular a coincidir. |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | La propiedad que indica si los caracteres ilegibles se omiten durante la comparación de cadenas. |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | La lista de números de página específicos. (heredado de [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Guides
Guías de tareas que usan `TextSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
