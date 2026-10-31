---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 WordProcessingImageEffects 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.watermark.options.word_processing import WordProcessingImageEffects
from groupdocs.watermark.watermarks import Color

# 为水印创建默认图像效果
effects = WordProcessingImageEffects()
effects.brightness = 0.7
effects.contrast = 0.6
effects.chroma_key = Color.red
```

### 另请参见
* class [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/)
