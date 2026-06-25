---
title: Font class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Represents a font.

The Font type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Initializes a new Font instance with a specified font family name and size. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initializes a new Font with the specified font family name, size, and style. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initializes a Font with a custom font family name, a folder path containing TrueType font files, a size, and a style. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initializes a new instance of the [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/) class with a specified custom font family name, folder path containing TrueType font files, and a size. |

### Properties
| Property | Description |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | The font is bold. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | The family name of this Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | The folder that contains TrueType font files. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | The font is italic. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | The size of this Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | The font specifies a horizontal line through the characters. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | The style information for this [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/). |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | The font is underlined. |

### Example

```python
import groupdocs.watermark.watermarks as gww

# Create a font using a custom TrueType font located in a folder
font = gww.Font("CustomFontName", r"c:\CustomFonts\", 36.0)
```

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
