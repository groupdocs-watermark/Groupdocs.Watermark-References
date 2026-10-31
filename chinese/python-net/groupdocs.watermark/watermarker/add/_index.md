---
title: "add 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "向已加载的文档添加水印。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

向已加载的文档添加水印。

了解在 GroupDocs 文档中添加水印的更多信息。

```python
def add(self, watermark):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| watermark | `Watermark` | 要添加到文档的水印。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

使用水印选项向已加载的文档添加水印。

了解有关添加水印的更多信息：https://docs.groupdocs.com/display/watermarknet/Adding+watermarks。

```python
def add(self, watermark, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| watermark | `Watermark` | 要添加到文档的水印。 |
| options | `WatermarkOptions` | 添加水印时使用的其他选项。 |

**Returns:** None.

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
