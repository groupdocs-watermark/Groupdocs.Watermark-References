---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用起始角度和结束角度初始化 RotateAngleSearchCriteria 的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

使用起始角度和结束角度初始化 RotateAngleSearchCriteria 的新实例。

```python
def __init__(self, min_angle, max_angle):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| min_angle | `float` | 起始角度（单位：度）。 |
| max_angle | `float` | 结束角度，单位为度。 |

### 示例

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# 搜索旋转角度在 30 到 60 度之间的水印
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### 另请参见
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
