---
title: "SizeSearchCriteria 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示允许按水印大小过滤的条件。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

表示允许按水印大小过滤的条件。

了解更多：
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SizeSearchCriteria 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | 使用指定的维度、起始值和结束值初始化 SizeSearchCriteria 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | 使用逻辑 AND 运算符将此 SearchCriteria 与其他条件组合。（继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | （继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | 对该 SearchCriteria 取反。（继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | 使用逻辑 OR 运算符将此 SearchCriteria 与其他条件组合。（继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | （继承自 [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | 用于搜索的水印维度。 |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | 结束值。 |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | 起始值。 |

### 示例

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.common import Dimension
from groupdocs.watermark.search.search_criteria import SizeSearchCriteria, RotateAngleSearchCriteria, TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    width_range = SizeSearchCriteria(Dimension.WIDTH, 50, 100)
    rotate_angle = RotateAngleSearchCriteria(0, 45)
    text_criteria = TextSearchCriteria(re.compile(r"^Test watermark$"))
    watermarks = watermarker.search(text_criteria.and_(width_range.or_(rotate_angle)))
    watermarks.clear()
    watermarker.save("./output.pdf")
```

### 另请参见
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
