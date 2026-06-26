---
title: TextWatermark class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a text watermark."
type: docs
url: /python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Represents a text watermark.

Learn more:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

The TextWatermark type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Initializes a new instance of the [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) class with a specified text and a font. |

### Properties
| Property | Description |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | The background color of the text. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | The font of the text. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | The foreground color of the text. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | The padding settings of this TextWatermark, applicable only to image files. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | The text used as watermark. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | The watermark text alignment. |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | The property indicating whether the watermark size and coordinates are calculated considering parent margins. If set to True, calculations consider parent margins; otherwise, margins are ignored (default is False). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | The desired height of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | The horizontal alignment of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | The watermark is placed in the background when True; otherwise it appears in the foreground (top). The default is False. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | The margin settings of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | The opacity of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | The pages setup settings of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | The rotate angle of this Watermark in degrees. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | The property indicates whether to save information about added watermarks in the document metadata. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | The scale factor of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | The sizing type specifying how the watermark should be sized. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | The options to define a repeated watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | The vertical alignment of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | The desired width of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | The x-coordinate of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | The y-coordinate of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

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

### Guides
Task guides that use `TextWatermark`:

* [AI agents and LLM integration](/watermark/python-net/guides/agents-and-llm-integration/)
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
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Quick Start Guide](/watermark/python-net/guides/quick-start-guide/)
* [GroupDocs.Watermark for Python via .NET Overview](/watermark/python-net/guides/product-overview/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
