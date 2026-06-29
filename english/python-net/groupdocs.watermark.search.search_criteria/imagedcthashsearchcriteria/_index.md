---
title: ImageDctHashSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a search criteria for finding images in a document."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

Represents a search criteria for finding images in a document.

This search criteria uses DCT‑based perceptual image hash for calculating image similarity.

- Learn more: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

The ImageDctHashSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | Initializes a new instance of the ImageDctHashSearchCriteria class with a specified file path. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | Initializes a new instance of the ImageDctHashSearchCriteria class with a specified stream. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | The maximum allowed difference between images. (inherited from [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | The list of specific page numbers. (inherited from [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc

with gw.Watermarker("watermarked-sample.docx") as watermarker:
    criteria = gws_sc.ImageDctHashSearchCriteria("logo.png")
    criteria.max_difference = 0.9
    possible = watermarker.search(criteria)
    possible.clear()
    watermarker.save("clean-sample.docx")
```

### Guides
Task guides that use `ImageDctHashSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### See Also
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
