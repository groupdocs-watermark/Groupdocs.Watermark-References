---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Initializes a new Font instance with a specified font family name and size.

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
import groupdocs.watermark.watermarks as gww

font = gww.Font("Arial", 8.0)
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
import groupdocs.watermark.watermarks as gww

font = gww.Font("Arial", 12.0, gww.FontStyle.Regular)
```

## __init__ {#font_family_name-folder_path-size}

Initializes a Font with a custom font family name, a folder path containing TrueType font files, a size, and a style.

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
import groupdocs.watermark.watermarks as gww

fonts_folder = r"c:\\CustomFonts\\"
font = gww.Font("CustomFontName", fonts_folder, 36.0)
```

## __init__ {#font_family_name-folder_path-size-style}

Initializes a new instance of the [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/) class with a specified custom font family name, folder path containing TrueType font files, and a size.

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
import groupdocs.watermark.watermarks as gww

fonts_folder = r"c:\\CustomFonts\\"
font = gww.Font("CustomFontName", fonts_folder, 36.0)
```

### See Also
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
