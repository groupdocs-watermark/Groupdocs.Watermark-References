---
title: SizeSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

Represents criteria allowing filtering by watermark size.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

The SizeSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | Initializes a new SizeSearchCriteria with a specified dimension, a starting value and an ending value. |

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
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | The dimension of watermark to search by. |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | The ending value. |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | The starting value. |

### Example

```python
import re
from groupdocs.watermark import Watermarker, SizeSearchCriteria, Dimension, RotateAngleSearchCriteria, TextSearchCriteria

with Watermarker(r"C:\test.some_ext") as watermarker:
    width_range = SizeSearchCriteria(Dimension.Width, 50, 100)
    rotate_angle = RotateAngleSearchCriteria(0, 45)
    text_criteria = TextSearchCriteria(re.compile(r"^Test watermark$"))
    watermarks = watermarker.search(text_criteria.and_(width_range.or_(rotate_angle)))
    watermarks.clear()
    watermarker.save()
```

### See Also
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
