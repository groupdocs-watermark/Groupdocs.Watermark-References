---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new TextSearchCriteria with a specified regular expression."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Initializes a new TextSearchCriteria with a specified regular expression.

```python
def __init__(self, pattern):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | The regular expression to match. |

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Initializes a new instance of the [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) class with a search string and a flag for case‑sensitive comparison.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_string | `str` | The exact string to search for. |
| is_match_case | `bool` | False to ignore case during the comparison; otherwise, True. |

### Example

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Initializes a new instance of the [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) class with a search string.

```python
def __init__(self, search_string):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_string | `str` | The exact string to search for. |

### Example

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

### See Also
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
