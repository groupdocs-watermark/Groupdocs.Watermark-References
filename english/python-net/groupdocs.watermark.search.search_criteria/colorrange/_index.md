---
title: ColorRange class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a range of colors using HSB representation of RGB color."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Represents a range of colors using HSB representation of RGB color.

The ColorRange type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Initializes a new instance of the [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) class. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Initializes a new instance of [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) with a specified exact color. |

### Properties
| Property | Description |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | The flag indicating whether only the empty color is in range. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | The ending brightness value, ranging from 0.0 (black) to 1.0 (white). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | The ending hue value, in degrees. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | The ending saturation value. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | The starting brightness value, ranging from 0.0 (black) to 1.0 (white). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | The starting hue value, in degrees. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | The starting saturation value. |

### Example

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Create a color range for foreground color matching
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Task guides that use `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### See Also
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
