---
title: searchable_objects property
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/searchable_objects/
is_root: false
weight: 100
---

## searchable_objects property


Gets or sets the content objects that are to be included in a watermark search.

### Remarks 


This property also specifies content objects which are used in image search.
For more information see [`Watermarker.search`](/watermark/python-net/groupdocs.watermark/watermarker/search)
and [`Watermarker.get_images`](/watermark/python-net/groupdocs.watermark/watermarker/get_images) methods.


Learn more about searching watermarks:
[Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Example 


Remove all XObjects and Artifacts from a pdf document.
### Definition:
```python
@property
def searchable_objects(self):
    ...
@searchable_objects.setter
def searchable_objects(self, value):
    ...
```

### See Also
* module [`groupdocs.watermark`](../../)
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects)
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker)
