---
title: remove method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 60
---

## remove {#groupdocs.watermark.search.PossibleWatermark}

Removes watermark from the document.



```python
def remove(self, possible_watermark):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| possible_watermark | groupdocs.watermark.search.PossibleWatermark | The watermark to remove. |

### Example 


Find and remove the first possible watermark containing particular text or image from a document
of any supported type.


## remove {#groupdocs.watermark.search.PossibleWatermarkCollection}

Removes all watermarks in the collection from the document.



```python
def remove(self, possible_watermarks):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| possible_watermarks | groupdocs.watermark.search.PossibleWatermarkCollection | The collection of watermarks to remove. |

### Example 


Find and remove all possible watermarks containing particular text or image from a document
of any supported type.



### See Also
* module [`groupdocs.watermark`](../../)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
