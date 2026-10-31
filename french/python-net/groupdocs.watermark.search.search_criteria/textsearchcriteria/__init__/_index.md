---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise un nouveau TextSearchCriteria avec une expression régulière spécifiée."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Initialise un nouveau TextSearchCriteria avec une expression régulière spécifiée.

```python
def __init__(self, pattern):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | L'expression régulière à faire correspondre. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Initialise une nouvelle instance de la classe [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) avec une chaîne de recherche et un indicateur pour la comparaison sensible à la casse.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_string | `str` | La chaîne exacte à rechercher. |
| is_match_case | `bool` | Faux pour ignorer la casse lors de la comparaison ; sinon, Vrai. |

### Exemple

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Initialise une nouvelle instance de la classe [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) avec une chaîne de recherche.

```python
def __init__(self, search_string):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_string | `str` | La chaîne exacte à rechercher. |

### Exemple

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

### Voir aussi
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
