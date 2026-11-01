---
title: "método search"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Busca todas las marcas de agua posibles en el documento."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Busca todas las marcas de agua posibles en el documento.

La búsqueda se realiza en los objetos especificados en [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Obtenga más información sobre la búsqueda de marcas de agua https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

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

## search {#search_criteria}

Busca marcas de agua posibles según los criterios de búsqueda especificados.

La búsqueda se realiza en los objetos especificados en [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Obtenga más información sobre la búsqueda de marcas de agua: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Los criterios de búsqueda a usar. |

**Returns:** The collection of possible watermarks.

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

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
