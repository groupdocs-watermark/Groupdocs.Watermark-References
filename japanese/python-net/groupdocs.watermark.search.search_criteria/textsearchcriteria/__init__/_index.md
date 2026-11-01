---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された正規表現で新しい TextSearchCriteria を初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

指定された正規表現で新しい TextSearchCriteria を初期化します。

```python
def __init__(self, pattern):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | 一致させる正規表現です。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

検索文字列と大文字小文字を区別する比較のフラグを使用して、[`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self, search_string, is_match_case):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| search_string | `str` | 検索対象の正確な文字列です。 |
| is_match_case | `bool` | 比較時に大文字小文字を無視する場合は False、そうでない場合は True。 |

### 例

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

検索文字列を使用して、[`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self, search_string):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| search_string | `str` | 検索対象の正確な文字列です。 |

### 例

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

### 関連項目
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
