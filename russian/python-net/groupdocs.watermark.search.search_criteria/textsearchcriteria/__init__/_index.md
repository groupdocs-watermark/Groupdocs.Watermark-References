---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый TextSearchCriteria с указанным регулярным выражением."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

Инициализирует новый TextSearchCriteria с указанным регулярным выражением.

```python
def __init__(self, pattern):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | Регулярное выражение для сопоставления. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

Инициализирует новый экземпляр класса [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) с поисковой строкой и флагом чувствительности к регистру.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_string | `str` | Точная строка для поиска. |
| is_match_case | `bool` | False, чтобы игнорировать регистр при сравнении; иначе — True. |

### Пример

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

Инициализирует новый экземпляр класса [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) с поисковой строкой.

```python
def __init__(self, search_string):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_string | `str` | Точная строка для поиска. |

### Пример

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

### См. также
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
