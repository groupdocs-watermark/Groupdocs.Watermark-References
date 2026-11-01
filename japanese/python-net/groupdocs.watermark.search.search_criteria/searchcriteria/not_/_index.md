---
title: "not_ メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "この SearchCriteria を否定します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

この SearchCriteria を否定します。

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### 例

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

### 関連項目
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
