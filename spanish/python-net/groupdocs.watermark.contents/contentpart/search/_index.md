---
title: "método search"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Encuentra marcas de agua posibles según los criterios de búsqueda especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Los criterios de búsqueda a usar. |

**Returns:** The collection of the possible watermarks.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Encuentra todas las posibles marcas de agua en el contenido.

La búsqueda se realiza en los objetos especificados en [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Ver también
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
