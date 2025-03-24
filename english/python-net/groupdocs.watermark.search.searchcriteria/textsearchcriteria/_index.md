---
title: TextSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
is_root: false
weight: 160
---

## TextSearchCriteria class

Represents criteria allowing filtering by watermark text.



**Inheritance:** [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria) → 
[`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria) → 
[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)



The TextSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/__init__/#str-bool) | Initializes a new instance of the [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria) class<br/>with a search string and a flag for comparison. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/__init__/#str) | Initializes a new instance of the [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria) class with a search string. |


### Properties
| Property | Description |
| :- | :- |
| [pages](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/pages) | Gets or sets the list of specific page numbers |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/skip_unreadable_characters) | Gets or sets a value indicating that unreadable characters will be skipped during string comparison. |


### Methods
| Method | Description |
| :- | :- |
| [both](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/both/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical AND operator. |
| [either](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/either/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical OR operator. |
| [is_not](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/is_not/#) | Negates this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria). |



### Remarks 


**Learn more:** |
|
 |

### Example 


Find and remove watermark using search criteria.

### See Also
* module [`groupdocs.watermark.search.searchcriteria`](..)
* class [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/pagesearchcriteria)
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textsearchcriteria)
