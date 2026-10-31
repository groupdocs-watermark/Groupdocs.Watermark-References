---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 PagesSetup 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/) 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

使用指定参数初始化新的 PagesSetup 实例。

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| all_pages | `bool` | 是否包含所有页面。 |
| first_page | `bool` | 是否包含第一页。 |
| last_page | `bool` | 是否包含最后一页。 |
| odd_pages | `bool` | 是否包含奇数页。 |
| even_pages | `bool` | 是否包含偶数页。 |
| pages | `List[int]` | 要包含的特定页码列表。 |
| page_number | `Optional[int]` | 当前页面的索引。 |

### 另请参见
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
