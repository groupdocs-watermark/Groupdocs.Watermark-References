---
title: create_page_stream property
second_title: GroupDocs.Watermark for Python via .NET API References
description: "The page stream creation delegate used to obtain a writable stream for each rendered page."
type: docs
url: /python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

The page stream creation delegate used to obtain a writable stream for each rendered page.

GroupDocs.Watermark renders document pages as images. Supply a callable that receives a page number (`int`) and returns a writable `io.RawIOBase` stream; the library writes the rendered image to the stream and closes it.

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
