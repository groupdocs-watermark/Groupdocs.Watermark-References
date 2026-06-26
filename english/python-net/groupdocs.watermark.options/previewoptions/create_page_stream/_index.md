---
title: create_page_stream property
second_title: GroupDocs.Watermark for Python via .NET API References
description: "The page stream creation delegate."
type: docs
url: /python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

The page stream creation delegate.

The delegate is called with the page number (`int`) and should return an `io.RawIOBase` stream that the preview generator will write the preview image to.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### See Also
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
