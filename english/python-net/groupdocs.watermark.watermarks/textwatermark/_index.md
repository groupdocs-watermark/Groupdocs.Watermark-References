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

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
