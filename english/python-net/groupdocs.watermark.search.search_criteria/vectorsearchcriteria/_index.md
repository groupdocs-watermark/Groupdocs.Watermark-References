---
title: VectorSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
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
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Initializes a new instance of the [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/) class. |

### Methods
| Method | Description |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) with other criteria using logical AND operator. (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) |  (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negates the SearchCriteria. (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combines this SearchCriteria with other criteria using logical OR operator. (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) |  (inherited from [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Properties
| Property | Description |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | The range of colors used to filter vector watermarks by foreground color. |

### Example

```python
from GroupDocs.Watermark import Watermarker, VectorSearchCriteria
from GroupDocs.Watermark.Watermarks import Color, ColorRange
from System.Drawing import ColorTranslator

with Watermarker(r"C:\test.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = ColorTranslator.FromHtml("#a9aaae")
    system_color = Color.FromArgb(watermark_color.A, watermark_color.R,
                                 watermark_color.G, watermark_color.B)
    criteria_vector_color_range = ColorRange(system_color)
    criteria_vector_color_range.MinBrightness = 0.1
    criteria_vector_color_range.MaxBrightness = 0.7
    search_criteria.VectorColorRange = criteria_vector_color_range

    possible_watermarks = watermarker.Search(search_criteria)
    possible_watermarks.Clear()
    watermarker.Save(r"C:\modified_test.pdf")
```

### See Also
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
