---
title: "search 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "搜索文档中所有可能的水印。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

搜索文档中所有可能的水印。

搜索在 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) 中指定的对象中进行。

了解更多关于搜索水印的信息 https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

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

## search {#search_criteria}

根据指定的搜索条件搜索可能的水印。

搜索在 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) 中指定的对象中进行。

了解更多关于搜索水印的信息: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | 要使用的搜索条件。 |

**Returns:** The collection of possible watermarks.

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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
