---
title: get_bytes method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/
is_root: false
weight: 1030
---


## get_bytes

Gets the image as a byte array.

```python
def get_bytes(self):
    ...
```

**Returns:** bytes: The image data.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gw.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    content = watermarker.get_content(gwc_ppt.PresentationContent)
    for slide in content.slides:
        bg = slide.image_fill_format.background_image
        if bg is not None:
            data = bg.get_bytes()
            print(len(data))
```

### See Also
* class [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)
