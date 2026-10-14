---
title: Font class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a font."
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
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Initializes a new Font instance with the specified font family name and size. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initializes a new Font instance with the specified font family name, size, and style. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initializes a new Font instance with a custom font family name, a folder containing TrueType fonts, a size, and a style. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initializes a new Font instance with a custom font family name, the folder containing the TrueType font files, and a size. |

### Properties
| Property | Description |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | The font is bold. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | The family name of this Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | The folder that contains TrueType font files. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | The font is italic. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | The size of this Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | The font specifies a horizontal line through the text. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | The style information for this Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | The font is underlined. |

### Example

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
Task guides that use `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
