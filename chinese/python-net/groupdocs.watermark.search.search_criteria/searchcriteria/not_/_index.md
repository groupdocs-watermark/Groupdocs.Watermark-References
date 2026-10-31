---
title: "not_ 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "对该 SearchCriteria 取反。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

对该 SearchCriteria 取反。

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_not():
    with Watermarker("./document.pdf") as watermarker:
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        not_criteria = text_criteria.not_()
        results = watermarker.search(not_criteria)
        print("Found", len(results), "watermarks that do NOT match the text")
```

### 另请参见
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
