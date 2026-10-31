---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的字体族名称和大小初始化新的 Font 实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

使用指定的字体族名称和大小初始化新的 Font 实例。

```python
def __init__(self, font_family_name, size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_family_name | `str` | 字体族名称。 |
| size | `float` | 新字体的大小。 |

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

## __init__ {#font_family_name-size-style}

使用指定的字体族名称、大小和样式初始化新的 Font 实例。

```python
def __init__(self, font_family_name, size, style):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_family_name | `str` | 字体族名称。 |
| size | `float` | 新字体的大小。 |
| style | `FontStyle` | 新字体的样式。 |

### 示例

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

使用自定义字体族名称、包含 TrueType 字体的文件夹、大小和样式初始化新的 Font 实例。

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_family_name | `str` | 字体族名称。 |
| folder_path | `str` | 包含 TrueType 字体文件的文件夹路径。 |
| size | `float` | 新字体的大小。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

fonts_folder = r"c:\CustomFonts"
with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark(
        "Test watermark",
        Font("CustomFontName", fonts_folder, 36.0)
    )
    watermark.foreground_color = Color.blue
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("./output.pdf")
```

## __init__ {#font_family_name-folder_path-size-style}

使用自定义字体族名称、包含 TrueType 字体文件的文件夹以及大小初始化新的 Font 实例。

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_family_name | `str` | 字体族名称。 |
| folder_path | `str` | 包含 TrueType 字体文件的文件夹路径。 |
| size | `float` | 新字体的大小。 |
| style | `FontStyle` |  |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark(
        "Test watermark",
        Font("CustomFontName", r"c:\CustomFonts", 36.0)
    )
    watermark.foreground_color = Color.blue
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("./output.pdf")
```

### 另请参见
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
