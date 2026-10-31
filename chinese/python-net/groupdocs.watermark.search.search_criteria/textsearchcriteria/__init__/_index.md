---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的正则表达式初始化新的 TextSearchCriteria。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

使用指定的正则表达式初始化新的 TextSearchCriteria。

```python
def __init__(self, pattern):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | 用于匹配的正则表达式。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

使用搜索字符串和区分大小写比较的标志，初始化 [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) 类的新实例。

```python
def __init__(self, search_string, is_match_case):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_string | `str` | 要搜索的精确字符串。 |
| is_match_case | `bool` | False 表示在比较时忽略大小写；否则为 True。 |

### 示例

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

使用搜索字符串，初始化 [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) 类的新实例。

```python
def __init__(self, search_string):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_string | `str` | 要搜索的精确字符串。 |

### 示例

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

### 另请参见
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
