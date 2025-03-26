---
title: ImageThumbnailSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
is_root: false
weight: 60
---

## ImageThumbnailSearchCriteria class

Represents search criteria for finding images in a content.



**Inheritance:** [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria) → 
[`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria) → 
[`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria) → 
[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)



The ImageThumbnailSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/__init__/#str) | Initializes a new instance of the [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria) class with a specified file path. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/__init__/#io.RawIOBase) | Initializes a new instance of the [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria) class with a specified stream. |


### Properties
| Property | Description |
| :- | :- |
| [pages](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/pages) | Gets or sets the list of specific page numbers |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/max_difference) | Gets or sets maximum allowed difference between images. |
| [thumbnail_size](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnail_size) | Gets or sets thumbnail size. |


### Methods
| Method | Description |
| :- | :- |
| [both](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/both/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical AND operator. |
| [either](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/either/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical OR operator. |
| [is_not](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/is_not/#) | Negates this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria). |



### Remarks 


This search criteria uses image binarized thumbnail for calculating image similarity.

### See Also
* module [`groupdocs.watermark.search.searchcriteria`](..)
* class [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria)
* class [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria)
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)
