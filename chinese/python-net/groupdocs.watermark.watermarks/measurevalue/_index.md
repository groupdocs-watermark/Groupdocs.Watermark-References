---
title: "MeasureValue 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示具有特定类型和数值的测量值。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

表示具有特定类型和数值的测量值。

MeasureValue 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | 测量的类型。 |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | 测量的数值；必须大于 0。 |

### 示例

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# 创建以页面百分比表示的测量
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
使用 `MeasureValue` 的任务指南：

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 另请参见
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
