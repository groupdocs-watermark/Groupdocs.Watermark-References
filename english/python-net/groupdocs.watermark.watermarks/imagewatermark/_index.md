---
title: ImageWatermark class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Represents an image watermark.

Learn more:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

The ImageWatermark type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Initializes a new ImageWatermark instance using the specified file path. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Initializes a new ImageWatermark instance using the provided image stream. |

### Methods
| Method | Description |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Disposes the current instance. |

### Properties
| Property | Description |
| :- | :- |
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

with gw.Watermarker("document.pdf") as watermarker:
    with gww.ImageWatermark("watermark.png") as watermark:
        watermarker.add(watermark)
        watermarker.save("document.pdf")
```

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
