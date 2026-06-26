---
title: VectorSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents criteria allowing filtering by watermark color."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

Represents criteria allowing filtering by watermark color.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

The VectorSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Initializes a new [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/) instance. |

### Methods
| Method | Description |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combines this SearchCriteria with other criteria using the logical AND operator. (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) |  (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negates this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/). (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combines this SearchCriteria with other criteria using logical OR operator. (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) |  (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Properties
| Property | Description |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | The range of colors used to filter vector watermarks by foreground color. |

### Example

```python
from groupdocs.watermark import Watermarker, VectorSearchCriteria, ColorRange, Color

# Open the document
watermarker = Watermarker(r"C:\test.pdf")

# Create search criteria
search_criteria = VectorSearchCriteria()

# Define the watermark color to filter by
watermark_color = Color.from_html("#a9aaae")

# Set the color range with brightness limits
criteria_vector_color_range = ColorRange(watermark_color)
criteria_vector_color_range.min_brightness = 0.1
criteria_vector_color_range.max_brightness = 0.7
search_criteria.vector_color_range = criteria_vector_color_range

# Search and remove watermarks
possible_watermark_collection = watermarker.search(search_criteria)
possible_watermark_collection.clear()

# Save the modified document
watermarker.save(r"C:\modified_test.pdf")
```

### See Also
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
