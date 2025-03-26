---
title: get_images method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 50
---

## get_images {#}

Finds all images in the document.


### Returns 


The collection of found images.


```python
def get_images(self):
    ...
```



### Example 


Add watermark to all images in a document of any supported type.


## get_images {#groupdocs.watermark.search.searchcriteria.ImageSearchCriteria}

Finds images according to specified search criteria.


### Returns 


The collection of found images.


```python
def get_images(self, search_criteria):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | groupdocs.watermark.search.searchcriteria.ImageSearchCriteria | The search criteria to use. |

### Example 


Remove all images that are similar to the reference from a document of any supported type.



### See Also
* module [`groupdocs.watermark`](../../)
* class [`WatermarkableImageCollection`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
