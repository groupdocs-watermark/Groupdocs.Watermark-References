---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο TextSearchCriteria με καθορισμένη κανονική έκφραση."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Αρχικοποιεί ένα νέο TextSearchCriteria με καθορισμένη κανονική έκφραση.

```python
def __init__(self, pattern):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | Η κανονική έκφραση για αντιστοίχιση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) με μια συμβολοσειρά αναζήτησης και μια σημαία για σύγκριση με διάκριση πεζών-κεφαλαίων.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_string | `str` | Η ακριβής συμβολοσειρά για αναζήτηση. |
| is_match_case | `bool` | Ψευδές για παράβλεψη πεζών/κεφαλαίων κατά τη σύγκριση· διαφορετικά, Αληθές. |

### Παράδειγμα

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) με μια συμβολοσειρά αναζήτησης.

```python
def __init__(self, search_string):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_string | `str` | Η ακριβής συμβολοσειρά για αναζήτηση. |

### Παράδειγμα

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

### Δείτε επίσης
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
