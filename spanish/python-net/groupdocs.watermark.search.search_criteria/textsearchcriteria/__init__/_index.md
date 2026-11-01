---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa un nuevo TextSearchCriteria con una expresión regular especificada."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Inicializa un nuevo TextSearchCriteria con una expresión regular especificada.

```python
def __init__(self, pattern):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | La expresión regular a coincidir. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Inicializa una nueva instancia de la clase [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una cadena de búsqueda y una bandera para comparación sensible a mayúsculas.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_string | `str` | La cadena exacta a buscar. |
| is_match_case | `bool` | False para ignorar mayúsculas/minúsculas durante la comparación; de lo contrario, True. |

### Ejemplo

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Inicializa una nueva instancia de la clase [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una cadena de búsqueda.

```python
def __init__(self, search_string):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_string | `str` | La cadena exacta a buscar. |

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
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
