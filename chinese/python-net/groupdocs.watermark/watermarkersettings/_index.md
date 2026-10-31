---
title: "WatermarkerSettings 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "定义用于自定义 Watermarker 行为的设置。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

定义用于自定义 Watermarker 行为的设置。

WatermarkerSettings 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | 初始化 WatermarkerSettings 的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | 在水印过程中用于记录事件和错误的日志记录器。 |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | 将在水印搜索中包含的可搜索对象。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | 获取该类的默认值。 |

### 示例

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
使用 `WatermarkerSettings` 的任务指南：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 另请参见
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
