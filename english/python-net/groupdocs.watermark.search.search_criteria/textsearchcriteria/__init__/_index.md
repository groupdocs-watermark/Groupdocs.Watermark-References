---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Initializes a new instance of [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) with a regular expression.

```python
def __init__(self, pattern):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | The regular expression to match. |

### Example

```python
import re
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    regex = re.compile(r"^© \d{4}$")
    criteria = gws_sc.TextSearchCriteria(regex)
    possible = watermarker.search(criteria)
    print("Found", possible.count, "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Initializes a new TextSearchCriteria with a search string and a case‑sensitivity flag.

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
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    text_criteria = gws_sc.TextSearchCriteria("© 2017")
    possible = watermarker.search(text_criteria)
    print("Found", possible.count, "possible watermark(s)")
```

## __init__ {#search_string}

Initializes a new instance of the TextSearchCriteria class with a search string.

```python
def __init__(self, search_string):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_string | `str` | The exact string to search for. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("document.pdf") as watermarker:
    text_criteria = gws_sc.TextSearchCriteria("© 2017")
    possible = watermarker.search(text_criteria)
    print("Found", possible.count, "possible watermark(s)")
```

### See Also
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
