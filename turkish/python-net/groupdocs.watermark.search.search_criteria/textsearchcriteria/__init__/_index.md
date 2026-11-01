---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen düzenli ifadeyle yeni bir TextSearchCriteria başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Belirtilen düzenli ifadeyle yeni bir TextSearchCriteria başlatır.

```python
def __init__(self, pattern):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | Eşleşecek düzenli ifade. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Arama dizesi ve büyük/küçük harfe duyarlı karşılaştırma için bir bayrak ile [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_string | `str` | Aranacak kesin string. |
| is_match_case | `bool` | Karşılaştırma sırasında büyük/küçük harfi yoksaymak için False; aksi takdirde True. |

### Örnek

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Arama dizesi ile [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, search_string):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_string | `str` | Aranacak kesin string. |

### Örnek

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

### Ayrıca Bakınız
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
