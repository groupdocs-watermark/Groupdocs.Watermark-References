---
title: DiagramPageWatermarkOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

Represents watermark adding options when adding a shape watermark to a particular page of a Visio document.

Learn more: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

The DiagramPageWatermarkOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | Initializes a new instance of the [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | The page index to add watermark to. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | The lock state of the shape in Visio. If true, shape editing is forbidden. (inherited from [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
from groupdocs.watermark import Watermarker, DiagramLoadOptions, TextWatermark, DiagramPageWatermarkOptions, Font

load_options = DiagramLoadOptions()
with Watermarker(r"D:\test.vsdx", load_options) as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42))
    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### See Also
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
