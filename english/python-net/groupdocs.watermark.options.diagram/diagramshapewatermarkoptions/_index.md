---
title: DiagramShapeWatermarkOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
is_root: false
weight: 50
---


## DiagramShapeWatermarkOptions class

Represents watermark adding options when adding shape watermark to a Visio document.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

The DiagramShapeWatermarkOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/__init__/) | Initializes a new instance of the [`DiagramShapeWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [placement_type](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placement_type/) | The value specifying to what pages a watermark should be added. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | The lock state of the shape in Visio. If true, shape editing is forbidden. (inherited from [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
from groupdocs.watermark import (
    Watermarker,
    DiagramLoadOptions,
    TextWatermark,
    Font,
    DiagramShapeWatermarkOptions,
    DiagramWatermarkPlacementType,
)

load_options = DiagramLoadOptions()
with Watermarker(r"D:\test.vsdx", load_options) as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42))
    options = DiagramShapeWatermarkOptions()
    options.is_locked = True
    options.placement_type = DiagramWatermarkPlacementType.ALL_PAGES  # default
    watermarker.add(watermark, options)
    watermarker.save()
```

### See Also
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
