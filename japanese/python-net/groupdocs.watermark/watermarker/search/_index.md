---
title: "search メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメント内のすべての可能な透かしを検索します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

ドキュメント内のすべての可能な透かしを検索します。

検索は、[`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

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

## search {#search_criteria}

指定された検索基準に従って可能な透かしを検索します。

検索は、[`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | 使用する検索条件です。 |

**Returns:** The collection of possible watermarks.

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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
