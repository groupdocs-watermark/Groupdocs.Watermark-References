---
title: find_images method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.presentation/presentationbaseslide/find_images/
is_root: false
weight: 20
---

## find_images {#}

Finds all images in the content.
The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects).


### Returns 


The collection of the found images.


```python
def find_images(self):
    ...
```




## find_images {#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria}

Finds images according to the specified search criteria.
The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker#searchable_objects).


### Returns 


The collection of the found images.


```python
def find_images(self, search_criteria):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | groupdocs.watermark.search.searchcriteria.ImageSearchCriteria | The search criteria to use. |



### See Also
* module [`groupdocs.watermark.contents.presentation`](../../)
* class [`PresentationBaseSlide`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationbaseslide)
* class [`WatermarkableImageCollection`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimagecollection)
