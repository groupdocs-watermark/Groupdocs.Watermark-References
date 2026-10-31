---
title: "or_ 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用逻辑 OR 运算符将此 SearchCriteria 与其他条件组合。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

使用逻辑 OR 运算符将此 SearchCriteria 与其他条件组合。

```python
def or_(self, other):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | `SearchCriteria` | 用于组合的搜索条件。 |

**Returns:** SearchCriteria: Combined search criteria.

### 示例

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import (
        ImageDctHashSearchCriteria,
        TextSearchCriteria,
    )

    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        combined = image_criteria.or_(text_criteria)
        results = watermarker.search(combined)
        print(f"Found {len(results)} possible watermark(s)")
    ```

### 另请参见
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
