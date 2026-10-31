---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用在搜索过程后获得的唯一水印标识符初始化 ImageWatermarkResult。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks.results/imagewatermarkresult/__init__/
is_root: false
weight: 10
---


## __init__ {#watermark_id}

使用在搜索过程后获得的唯一水印标识符初始化 ImageWatermarkResult。该标识符用于从文档的水印信息层检索水印的其他属性。

```python
def __init__(self, watermark_id):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| watermark_id | `str` | 唯一水印标识符由 `GroupDocs.Signature.Signature` 的 `Sign` 或 `Search` 方法获取。 |

### 另请参见
* class [`ImageWatermarkResult`](/watermark/python-net/groupdocs.watermark.watermarks.results/imagewatermarkresult/)
