---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza un nuovo TextSearchCriteria con un'espressione regolare specificata."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Inizializza un nuovo TextSearchCriteria con un'espressione regolare specificata.

```python
def __init__(self, pattern):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | L'espressione regolare da corrispondere. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Inizializza una nuova istanza della classe [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una stringa di ricerca e un flag per il confronto sensibile al maiuscolo/minuscolo.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_string | `str` | La stringa esatta da cercare. |
| is_match_case | `bool` | False per ignorare maiuscole/minuscole durante il confronto; altrimenti, True. |

### Esempio

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Inizializza una nuova istanza della classe [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una stringa di ricerca.

```python
def __init__(self, search_string):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_string | `str` | La stringa esatta da cercare. |

### Esempio

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

### Vedi anche
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
