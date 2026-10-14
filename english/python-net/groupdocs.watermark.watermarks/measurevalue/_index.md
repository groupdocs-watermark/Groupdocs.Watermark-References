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
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | The numerical value of the measurement; it must be greater than 0. |

### Example

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Create a measurement expressed as a percentage of the page
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Task guides that use `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### See Also
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
