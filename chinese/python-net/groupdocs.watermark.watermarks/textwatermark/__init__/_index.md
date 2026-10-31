---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的文本和字体初始化新的 TextWatermark。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

使用指定的文本和字体初始化新的 TextWatermark。

```python
def __init__(self, text, font):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 用作水印的文本。 |
| font | `Font` | 文本的字体。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### 另请参见
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
