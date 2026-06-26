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
    from groupdocs.watermark.watermarks import Font, TextWatermark

    # Create a font with Arial family and size 48 points
    font = Font("Arial", 48)

    # Use the font in a text watermark
    watermark = TextWatermark("CONFIDENTIAL", font)
    ```

## __init__ {#font_family_name-size-style}

Initializes a new Font with the specified font family name, size, and style.

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

Initializes a new Font instance with a custom font family name, the folder containing the TrueType font files, and a size.

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
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

fonts_folder = r"c:\\CustomFonts\\"
with gw.Watermarker("test.pdf") as watermarker:
    font = gww.Font("CustomFontName", fonts_folder, 36.0)
    watermark = gww.TextWatermark("Test watermark", font)
    watermarker.add(watermark)
    watermarker.save("result.pdf")
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
from groupdocs.watermark.watermarks import Font

fonts_folder = r"C:\\CustomFonts\\"
font = Font("CustomFontName", fonts_folder, 36.0)
```

### See Also
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
