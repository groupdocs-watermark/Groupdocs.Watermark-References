---
title: MeasureValue class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a measurement value with a specific type and numerical value."
type: docs
url: /python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Represents a measurement value with a specific type and numerical value.

The MeasureValue type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Properties
| Property | Description |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | The type of measurement. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | The numerical value of the measurement. |

### Example

```python
import groupdocs.watermark.watermarks as gww

# Create a measurement of 12 percent
value = gww.MeasureValue(gww.TileMeasureType.PERCENT, 12)
```

### Guides
Task guides that use `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
