---
title: ImageDctHashSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---

## ImageDctHashSearchCriteria class

Represents a search criteria for finding images in a document.



**Inheritance:** [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria) → 
[`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria) → 
[`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria) → 
[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)



The ImageDctHashSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/__init__/#str) | Initializes a new instance of the [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria) class with a specified file path. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/__init__/#io.RawIOBase) | Initializes a new instance of the [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria) class with a specified stream. |


### Properties
| Property | Description |
| :- | :- |
| [pages](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/pages) | Gets or sets the list of specific page numbers |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/max_difference) | Gets or sets maximum allowed difference between images. |


### Methods
| Method | Description |
| :- | :- |
| [both](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/both/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical AND operator. |
| [either](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/either/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical OR operator. |
| [is_not](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/is_not/#) | Negates this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria). |



### Remarks 


This search criteria uses DCT based perceptual image hash for calculating image similarity.
**Learn more:** |
|
 |

### Example 


Search for images in the attached files (pdf).

### See Also
* module [`groupdocs.watermark.search.searchcriteria`](..)
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria)
* class [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria)
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)
