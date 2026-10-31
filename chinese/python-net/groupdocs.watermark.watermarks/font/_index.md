---
title: "Font 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示一种字体。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

表示一种字体。

Font 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | 使用指定的字体族名称和大小初始化新的 Font 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | 使用指定的字体族名称、大小和样式初始化新的 Font 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | 使用自定义字体族名称、包含 TrueType 字体的文件夹、大小和样式初始化新的 Font 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | 使用自定义字体族名称、包含 TrueType 字体文件的文件夹以及大小初始化新的 Font 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | 该字体为粗体。 |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | 此 Font 的族名称。 |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | 包含 TrueType 字体文件的文件夹。 |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | 该字体为斜体。 |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | 此 Font 的大小。 |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | 该字体在文本上绘制水平线。 |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | 此 Font 的样式信息。 |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | 该字体带下划线。 |

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

### Guides
使用 `Font` 的任务指南：

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 另请参见
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
