---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.image/tiffimageloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`TiffImageLoadOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/) class.

```python
def __init__(self):
    ...
```

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.image as gwo_img

load_options = gw.TiffImageLoadOptions()
with gw.Watermarker("image.tiff", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))
    options = gwo_img.TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save("image.tiff")
```

### See Also
* class [`TiffImageLoadOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/)
