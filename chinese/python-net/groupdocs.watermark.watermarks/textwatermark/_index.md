---
title: "TextWatermark 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示文本水印。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

表示文本水印。

了解更多：
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

TextWatermark 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | 使用指定的文本和字体初始化新的 TextWatermark。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | 文本的背景颜色。 |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | 文本的字体。 |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | 文本的前景颜色。 |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | 此 TextWatermark 的填充设置，仅适用于图像文件。 |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | 用作水印的文本。 |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | 水印文本对齐方式。 |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | 指示是否在计算水印大小和坐标时考虑父级边距的属性。如果设置为 True，计算将考虑父级边距；默认情况下该值为 False，父级边距将被忽略。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的期望高度。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | 此 Watermark 的水平对齐方式。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | 指示水印是否应放置在背景中的属性。如果为 true，水印放置在底部；否则放置在顶部（默认是 False）。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | 此 Watermark 的边距设置。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的不透明度。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | 此 Watermark 的页面设置。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的旋转角度（以度为单位）。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | 指示是否将添加的水印信息保存到文档元数据中的属性。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的缩放因子，定义水印大小如何随父级大小而变化。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | 水印的尺寸类型。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | 定义重复水印的选项。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的垂直对齐方式。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的期望宽度。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的 x 坐标。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的 y 坐标。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |

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

### Guides
使用 `TextWatermark` 的任务指南：

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 另请参见
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
