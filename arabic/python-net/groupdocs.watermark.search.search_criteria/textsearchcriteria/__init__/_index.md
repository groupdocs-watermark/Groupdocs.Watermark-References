---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من TextSearchCriteria بتعبير نمطي محدد."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

يُنشئ مثيلاً جديدًا من TextSearchCriteria بتعبير نمطي محدد.

```python
def __init__(self, pattern):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | التعبير النمطي للمطابقة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

يُنشئ مثيلاً جديدًا من الفئة [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) باستخدام سلسلة بحث وعلامة للمقارنة حساسة لحالة الأحرف.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_string | `str` | السلسلة الدقيقة للبحث عنها. |
| is_match_case | `bool` | خطأ لتجاهل حالة الأحرف أثناء المقارنة؛ وإلا، صحيح. |

### مثال

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

يُنشئ مثيلاً جديدًا من الفئة [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) باستخدام سلسلة بحث.

```python
def __init__(self, search_string):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_string | `str` | السلسلة الدقيقة للبحث عنها. |

### مثال

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

### انظر أيضًا
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
