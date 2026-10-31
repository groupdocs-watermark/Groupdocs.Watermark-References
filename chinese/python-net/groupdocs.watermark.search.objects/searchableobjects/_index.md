---
title: "SearchableObjects 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "指定要包含在水印搜索中的文档对象。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

指定要包含在水印搜索中的文档对象。

了解更多：
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SearchableObjects 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | 初始化 [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | 在 Visio 文档中将被包含在水印搜索的对象。 |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | 在电子邮件消息中将被包含在水印搜索的对象。 |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | 在 PDF 文档中将被包含在水印搜索的对象。 |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | 在 PowerPoint 文档中将被包含在水印搜索的对象。 |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | 在 Excel 文档中将被包含在水印搜索的对象。 |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | 在 Word 文档中将被包含在水印搜索的对象。 |

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
使用 `SearchableObjects` 的任务指南：

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 另请参见
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
