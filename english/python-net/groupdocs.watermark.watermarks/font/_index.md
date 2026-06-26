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
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initializes a new Font with the specified font family name, size, and style. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initializes a new Font instance with a custom font family name, the folder containing the TrueType font files, and a size. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initializes a new Font instance with a custom font family name, the folder containing the TrueType font files, and a size. |

### Properties
| Property | Description |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | The font is bold. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | The family name of this Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | The folder that contains TrueType font files. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | The font is italic. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | The size of this Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | The font specifies whether it has a horizontal line through the characters. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | The style of this Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | The font is underlined. Returns True if the font is underlined; otherwise, False. |

### Example

```python
from groupdocs.watermark.watermarks import Font

fonts_folder = r"C:\CustomFonts"
# Create a font using a custom TrueType font located in fonts_folder
font = Font("CustomFontName", fonts_folder, 36.0)
```

### Guides
Task guides that use `Font`:

* [Adding watermark to images inside a document](/watermark/python-net/guides/adding-watermark-to-images-inside-a-document/)
* [Rasterize document or page](/watermark/python-net/guides/rasterize-document-or-page/)
* [Watermarks in PDF document](/watermark/python-net/guides/watermarks-in-pdf-document/)
* [Working with slide backgrounds](/watermark/python-net/guides/working-with-slide-backgrounds/)
* [Working with spreadsheet document attachments](/watermark/python-net/guides/working-with-spreadsheet-document-attachments/)
* [Working with worksheet backgrounds](/watermark/python-net/guides/working-with-worksheet-backgrounds/)
* [Working with worksheet headers and footers](/watermark/python-net/guides/working-with-worksheet-headers-and-footers/)
* [Locking watermark in word processing document](/watermark/python-net/guides/locking-watermark-in-word-processing-document/)
* [Adding text watermarks](/watermark/python-net/guides/adding-text-watermarks/)
* [Result of added watermarks](/watermark/python-net/guides/result-of-added-watermarks/)
* [Modifying found watermark properties](/watermark/python-net/guides/modifying-found-watermark-properties/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Quick Start Guide](/watermark/python-net/guides/quick-start-guide/)
* [GroupDocs.Watermark for Python via .NET Overview](/watermark/python-net/guides/product-overview/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
