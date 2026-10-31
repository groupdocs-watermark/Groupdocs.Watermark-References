---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert ein neues TextSearchCriteria mit einem angegebenen regulären Ausdruck."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Initialisiert ein neues TextSearchCriteria mit einem angegebenen regulären Ausdruck.

```python
def __init__(self, pattern):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | Der reguläre Ausdruck zum Abgleichen. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Initialisiert eine neue Instanz der [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) Klasse mit einem Suchstring und einem Flag für die Groß‑/Kleinschreibung‑empfindliche Suche.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_string | `str` | Die genaue Zeichenkette, nach der gesucht wird. |
| is_match_case | `bool` | False, um die Groß-/Kleinschreibung beim Vergleich zu ignorieren; andernfalls True. |

### Beispiel

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Initialisiert eine neue Instanz der [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) Klasse mit einem Suchstring.

```python
def __init__(self, search_string):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_string | `str` | Die genaue Zeichenkette, nach der gesucht wird. |

### Beispiel

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

### Siehe auch
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
