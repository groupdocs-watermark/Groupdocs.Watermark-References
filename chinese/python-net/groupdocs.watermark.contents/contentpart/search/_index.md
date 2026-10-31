---
title: "search 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "根据指定的搜索条件查找可能的水印。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

根据指定的搜索条件查找可能的水印。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 列出的对象上执行。

```python
def search(self, search_criteria):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | 要使用的搜索条件。 |

**Returns:** The collection of the possible watermarks.

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

在内容中查找所有可能的水印。

搜索在 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) 中指定的对象中进行。

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### 另请参见
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
