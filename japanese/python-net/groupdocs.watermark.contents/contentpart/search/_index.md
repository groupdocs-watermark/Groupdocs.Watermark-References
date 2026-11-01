---
title: "search メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された検索条件に従って、可能性のある透かしを検索します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

指定された検索条件に基づいて可能性のある透かしを検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) に列挙されたオブジェクト上で実行されます。

```python
def search(self, search_criteria):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | 使用する検索条件です。 |

**Returns:** The collection of the possible watermarks.

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

コンテンツ内のすべての可能性のある透かしを検索します。

検索は、[`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) で指定されたオブジェクト内で実行されます。

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### 関連項目
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
