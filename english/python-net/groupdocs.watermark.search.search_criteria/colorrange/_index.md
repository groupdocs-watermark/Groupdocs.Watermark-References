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
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Initializes a new instance of the [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) class with a specified exact color. |

### Properties
| Property | Description |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | The flag indicating whether only the empty color is in range. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | The ending brightness value. The brightness ranges from 0.0 through 1.0, where 0.0 represents black and 1.0 represents white. |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | The ending hue value, in degrees. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | The ending saturation value. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | The starting brightness value. |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | The starting hue value, in degrees. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | The starting saturation value. The saturation ranges from 0.0 through 1.0, where 0.0 is grayscale and 1.0 is the most saturated. |

### Example

```python
import groupdocs.watermark.search.searchcriteria as gws_sc

# Create a color range for foreground colors
foreground_range = gws_sc.ColorRange()
foreground_range.min_hue = -5
foreground_range.max_hue = 10
foreground_range.min_brightness = 0.01
foreground_range.max_brightness = 0.99
```

### Guides
Task guides that use `ColorRange`:

* [Removing found watermarks](/watermark/python-net/guides/removing-found-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### See Also
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
