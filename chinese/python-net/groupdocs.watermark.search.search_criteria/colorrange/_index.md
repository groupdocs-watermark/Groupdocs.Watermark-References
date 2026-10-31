---
title: "ColorRange 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示使用 RGB 颜色的 HSB 表示法的颜色范围。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

表示使用 RGB 颜色的 HSB 表示法的颜色范围。

ColorRange 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | 初始化 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 类的新实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | 使用指定的精确颜色初始化 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | 指示是否仅空颜色在范围内的标志。 |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | 结束亮度值，范围从 0.0（黑）到 1.0（白）。 |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | 结束色相值，单位为度。 |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | 结束饱和度值。 |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | 起始亮度值，范围从 0.0（黑）到 1.0（白）。 |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | 起始色相值，单位为度。 |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | 起始饱和度值。 |

### 示例

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# 创建用于前景颜色匹配的颜色范围
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
使用 `ColorRange` 的任务指南：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 另请参见
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
