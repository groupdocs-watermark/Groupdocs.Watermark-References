---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new Font instance with the specified font family name and size."
type: docs
url: /python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Initializes a new Font instance with the specified font family name and size.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | The font family name. |
| size | `float` | The size of the new font. |

### Example

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

Initializes a new Font instance with the specified font family name, size, and style.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | The font family name. |
| size | `float` | The size of the new font. |
| style | `FontStyle` | The style of the new font. |

### Example

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Initializes a new Font instance with a custom font family name, a folder containing TrueType fonts, a size, and a style.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | The font family name. |
| folder_path | `str` | Folder path which contains TrueType font files. |
| size | `float` | The size of the new font. |

### Example

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

Initializes a new Font instance with a custom font family name, the folder containing the TrueType font files, and a size.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | The font family name. |
| folder_path | `str` | Folder path which contains TrueType font files. |
| size | `float` | The size of the new font. |
| style | `FontStyle` |  |

### Example

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

### See Also
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
