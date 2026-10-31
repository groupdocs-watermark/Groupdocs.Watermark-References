---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 WatermarkResult 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

使用特定值初始化新的 WatermarkResult 实例。

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_document_size | `int` | 源文档的大小（字节）。 |
| processing_time | `timedelta` | 处理时间（毫秒）。 |
| final_document_size | `int` | 最终处理的文档大小（字节）。 |
| number_watermarks_applied | `int` | 文档中应用的水印总数。 |

### 另请参见
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
