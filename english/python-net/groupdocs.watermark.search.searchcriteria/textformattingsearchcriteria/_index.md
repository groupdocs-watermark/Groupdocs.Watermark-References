---
title: TextFormattingSearchCriteria class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
is_root: false
weight: 150
---

## TextFormattingSearchCriteria class

Represents criteria allowing filtering by text formatting.



**Inheritance:** [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria) → 
[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)



The TextFormattingSearchCriteria type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/__init__/#) | Initializes a new instance of the [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria) class. |


### Properties
| Property | Description |
| :- | :- |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foreground_color_range) | Gets or sets the range of colors which are used to filter watermarks by text foreground color. |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/background_color_range) | Gets or sets the range of colors which are used to filter watermarks by text background color. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/font_name) | Gets or sets the name of the font which is used in possible watermark text formatting. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/min_font_size) | Gets or sets the starting value of the font size. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/max_font_size) | Gets or sets the ending value of the font size. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/font_bold) | Gets or sets a value indicating whether the font used in watermark text formatting is bold. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/font_italic) | Gets or sets a value indicating whether the font used in watermark text formatting is italic. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/font_underline) | Gets or sets a value indicating whether the font used in watermark text formatting is underline. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/font_strikeout) | Gets or sets a value indicating whether the font used in watermark text formatting is strikeout. |


### Methods
| Method | Description |
| :- | :- |
| [both](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/both/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical AND operator. |
| [either](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/either/#groupdocs.watermark.search.searchcriteria.SearchCriteria) | Combines this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria) with other criteria using logical OR operator. |
| [is_not](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/is_not/#) | Negates this [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria). |



### Remarks 


**Learn more:** |
|
 |

### Example 


Remove possible watermarks with a particular text formatting (regardless of document type).

### See Also
* module [`groupdocs.watermark.search.searchcriteria`](..)
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria)
