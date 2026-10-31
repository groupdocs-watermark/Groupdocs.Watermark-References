---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi TextSearchCriteria baru dengan ekspresi reguler yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Menginisialisasi TextSearchCriteria baru dengan ekspresi reguler yang ditentukan.

```python
def __init__(self, pattern):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | Ekspresi reguler untuk dicocokkan. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) dengan string pencarian dan flag untuk perbandingan yang sensitif huruf.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_string | `str` | String tepat untuk dicari. |
| is_match_case | `bool` | False untuk mengabaikan huruf besar/kecil selama perbandingan; jika tidak, True. |

### Contoh

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) dengan string pencarian.

```python
def __init__(self, search_string):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_string | `str` | String tepat untuk dicari. |

### Contoh

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

### Lihat Juga
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
