---
title: TextWatermark class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Represents a text watermark.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

The TextWatermark type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Initializes a new instance of the TextWatermark class with a specified text and a font. |

### Properties
| Property | Description |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | The background color of the text. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | The font of the text. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | The foreground color of the text. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | The padding settings of this TextWatermark. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | The text to be used as watermark. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | The watermark text alignment. |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | The consider_parent_margins property indicates whether the watermark size and coordinates are calculated considering parent margins. If set to True, margins are taken into account; otherwise (default False) they are ignored. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | The desired height of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | The horizontal alignment of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | The watermark is placed in the background when True; otherwise it is placed in the foreground (top). The default is False. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | The margin settings of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | The opacity of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | The pages setup settings of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | The rotate angle of this Watermark in degrees. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | The flag indicating whether information about added watermarks is saved in the document metadata. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | The scale factor of this Watermark, defining how the watermark size depends on the parent size. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | The sizing type specifying how the watermark should be sized. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | The options to define a repeated watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | The vertical alignment of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | The desired width of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | The x-coordinate of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | The y-coordinate of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("image.png") as watermarker:
    font = gww.Font("Calibri", 12.0)
    watermark = gww.TextWatermark("This is a test watermark", font)
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 0.5
    watermarker.add(watermark)
    watermarker.save("image.png")
```

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
