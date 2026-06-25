---
title: TileOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/tileoptions/
is_root: false
weight: 140
---


## TileOptions class

Represents options for configuring watermarks in tile mode.

The TileOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/__init__/) |  |

### Properties
| Property | Description |
| :- | :- |
| [line_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/line_spacing/) | The spacing between lines for watermarks in tile mode. |
| [rotate_around_origin](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/rotate_around_origin/) | The property indicates whether repeated watermarks are rotated around the bottom left point of the document; if `False`, rotation is relative to the left edge (default is `False`). |
| [tile_type](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/tile_type/) | The type of tile alignment for watermarks. |
| [watermark_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/watermark_spacing/) | The spacing between serials for watermarks in tile mode. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("sample.pdf") as watermarker:
    watermark = gww.ImageWatermark("watermark.jpg")
    watermark.tile_options = gww.TileOptions()
    watermark.tile_options.line_spacing = gww.MeasureValue(gww.TileMeasureType.PERCENT, 12)
    watermark.tile_options.watermark_spacing = gww.MeasureValue(gww.TileMeasureType.PERCENT, 10)
    watermarker.add(watermark)
    watermarker.save("result.pdf")
```

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
