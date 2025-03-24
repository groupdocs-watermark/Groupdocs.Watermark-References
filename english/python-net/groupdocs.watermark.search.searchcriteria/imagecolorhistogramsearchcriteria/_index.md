---
title: ImageColorHistogramSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
is_root: false
weight: 30
---

## ImageColorHistogramSearchCriteria class

Represents search criteria for finding images in a content.



**Inheritance:** [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria) → 
[`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria) → 
[`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria) → 
[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)



The ImageColorHistogramSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/__init__/#str) | Initializes a new instance of the [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria) class with a specified file path. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/__init__/#io.RawIOBase) | Initializes a new instance of the [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria) class with a specified stream. |


### Properties
| Property | Description |
| :- | :- |
| [pages](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/pages) | Gets or sets the list of specific page numbers |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/max_difference) | Gets or sets maximum allowed difference between images. |
| [bins_count](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/bins_count) | Gets or sets a count of bins that will be used for building color histograms. |


### Methods
| Method | Description |
| :- | :- |
| [both](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/both/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical AND operator. |
| [either](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/either/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical OR operator. |
| [is_not](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/is_not/#) | Negates this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria). |



### Remarks 


This search criteria uses image color histograms for calculating image similarity.

### See Also
* module [`groupdocs.watermark.search.searchcriteria`](..)
* class [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria)
* class [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria)
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)
