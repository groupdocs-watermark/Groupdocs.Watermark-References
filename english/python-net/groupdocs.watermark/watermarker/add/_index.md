---
title: add method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 20
---

## add {#groupdocs.watermark.Watermark}

Adds a watermark to the loaded document.



```python
def add(self, watermark):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| watermark | [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark) | The watermark to add to the document. |

### Example 


Add image and text watermark to a document of any supported type.


## add {#groupdocs.watermark.Watermark-groupdocs.watermark.options.WatermarkOptions}

Adds a watermark to the loaded document using watermark options.



```python
def add(self, watermark, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| watermark | [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark) | The watermark to add to the document. |
| options | groupdocs.watermark.options.WatermarkOptions | Additional options to use when adding the watermark. |

### Example 


Add an image watermark to a particular page of a pdf document.



### See Also
* module [`groupdocs.watermark`](../../)
* class [`AddWatermarkResult`](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
