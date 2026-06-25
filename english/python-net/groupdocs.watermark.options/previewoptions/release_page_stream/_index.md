---
title: release_page_stream property
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options/previewoptions/release_page_stream/
is_root: false
weight: 2050
---


## release_page_stream property

The page preview completion delegate.

A callable that is invoked after a page preview stream has been created. The callable receives the page number (`int`) and the preview stream (`io.RawIOBase`).

### Definition:
```python
@property
def release_page_stream(self):
    ...
@release_page_stream.setter
def release_page_stream(self, value):
    ...
```

### See Also
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
