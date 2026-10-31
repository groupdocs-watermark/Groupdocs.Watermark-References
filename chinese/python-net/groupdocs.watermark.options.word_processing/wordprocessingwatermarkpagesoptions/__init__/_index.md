---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 WordProcessingWatermarkPagesOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化 WordProcessingWatermarkPagesOptions 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# 创建将水印应用于特定页面的选项
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### 另请参见
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
