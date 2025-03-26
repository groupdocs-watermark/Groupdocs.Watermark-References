---
title: search method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.presentation/presentationslide/search/
is_root: false
weight: 30
---

## search {#}

Finds all possible watermarks in the content.
The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects).


### Returns 


The collection of the possible watermarks.


```python
def search(self):
    ...
```




## search {#groupdocs.watermark.search.searchcriteria.SearchCriteria}

Finds possible watermarks according to specified search criteria.
The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects).


### Returns 


The collection of the possible watermarks.


```python
def search(self, search_criteria):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | groupdocs.watermark.search.searchcriteria.SearchCriteria | The search criteria to use. |



### See Also
* module [`groupdocs.watermark.contents.presentation`](../../)
* class [`PossibleWatermarkCollection`](/watermark/python-net/groupdocs.watermark.search/possiblewatermarkcollection)
* class [`PresentationSlide`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationslide)
