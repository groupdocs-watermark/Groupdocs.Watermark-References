---
title: search method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 80
---

## search {#}

Searches all possible watermarks in the document.


### Returns 


The collection of possible watermarks.


```python
def search(self):
    ...
```



### Example 


Count the possible watermarks in a document of any supported type.


## search {#groupdocs.watermark.search.searchcriteria.SearchCriteria}

Searches possible watermarks according to specified search criteria.


### Returns 


The collection of possible watermarks.


```python
def search(self, search_criteria):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | groupdocs.watermark.search.searchcriteria.SearchCriteria | The search criteria to use. |

### Example 


Find and remove all possible watermarks containing particular text or image from a document
of any supported type.



### See Also
* module [`groupdocs.watermark`](../../)
* class [`PossibleWatermarkCollection`](/watermark/python-net/groupdocs.watermark.search/possiblewatermarkcollection)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
