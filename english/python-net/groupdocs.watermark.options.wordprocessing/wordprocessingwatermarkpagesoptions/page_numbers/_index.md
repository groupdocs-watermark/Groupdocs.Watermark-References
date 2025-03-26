---
title: page_numbers property
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/page_numbers/
is_root: false
weight: 90
---

## page_numbers property


Gets or sets the page numbers to add the watermark.

### Remarks 


All numbers must be greater than or equal to 1.
This property is only used when adding the watermark to a document.
If this value is `null` or empty, the watermark is added to all pages.
### Definition:
```python
@property
def page_numbers(self):
    ...
@page_numbers.setter
def page_numbers(self, value):
    ...
```

### See Also
* module [`groupdocs.watermark.options.wordprocessing`](../../)
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions)
