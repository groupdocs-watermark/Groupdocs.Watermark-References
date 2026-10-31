---
title: "RotateAngleSearchCriteria 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示允许按水印旋转角度过滤的条件。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

表示允许按水印旋转角度过滤的条件。

了解更多：
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

RotateAngleSearchCriteria 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | 使用起始角度和结束角度初始化 RotateAngleSearchCriteria 的新实例。 |

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
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | 结束角度，单位为度。 |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | 起始角度（单位：度）。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
使用 `RotateAngleSearchCriteria` 的任务指南：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 另请参见
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
