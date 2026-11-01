---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe TextSearchCriteria met een opgegeven reguliere expressie."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Initialiseert een nieuwe TextSearchCriteria met een opgegeven reguliere expressie.

```python
def __init__(self, pattern):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | De reguliere expressie om te matchen. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Initialiseert een nieuwe instantie van de [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) klasse met een zoekstring en een vlag voor hoofdlettergevoelige vergelijking.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_string | `str` | De exacte tekenreeks om naar te zoeken. |
| is_match_case | `bool` | False om hoofdlettergevoeligheid te negeren tijdens de vergelijking; anders True. |

### Voorbeeld

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Initialiseert een nieuwe instantie van de [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) klasse met een zoekstring.

```python
def __init__(self, search_string):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_string | `str` | De exacte tekenreeks om naar te zoeken. |

### Voorbeeld

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

### Zie ook
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
