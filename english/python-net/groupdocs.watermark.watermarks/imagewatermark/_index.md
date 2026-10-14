---
title: ImageWatermark class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents an image watermark."
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
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Initializes a new ImageWatermark instance with a specified file path. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Initializes a new ImageWatermark with the provided image stream. |

### Methods
| Method | Description |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Disposes the current instance. |

### Properties
| Property | Description |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | The property indicating whether the watermark size and coordinates are calculated considering parent margins. If set to True, calculations consider parent margins; by default the value is False and parent margins are ignored. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | The desired height of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | The horizontal alignment of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | The property indicating whether the watermark should be placed in the background. If true, the watermark is placed at the bottom; otherwise, it is placed at the top (default is False). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | The margin settings of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | The opacity of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | The pages setup settings of this Watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | The rotate angle of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) in degrees. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | The property indicates whether to save information about added watermarks in the document metadata. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | The scale factor of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), defining how watermark size depends on parent size. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | The sizing type of the watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | The options to define a repeated watermark. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | The vertical alignment of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | The desired width of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | The x-coordinate of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | The y-coordinate of this [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Example

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Load image data into a stream
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Open the document and add the image watermark
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Task guides that use `ImageWatermark`:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
