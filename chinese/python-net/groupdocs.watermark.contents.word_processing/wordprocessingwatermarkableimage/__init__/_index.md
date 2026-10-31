---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的图像数据初始化 WordProcessingWatermarkableImage 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

使用指定的图像数据初始化 [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) 类的新实例。

```python
def __init__(self, image_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_data | `list[int]` | 用于创建 `WordProcessingWatermarkableImage` 的无符号字节数组。 |

### 示例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### 另请参见
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
