---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 ColorRange 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# 创建默认颜色范围
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

使用指定的精确颜色初始化 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 的新实例。

```python
def __init__(self, exact_color):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| exact_color | `Color` | 用于创建范围的精确颜色。 |

### 另请参见
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
