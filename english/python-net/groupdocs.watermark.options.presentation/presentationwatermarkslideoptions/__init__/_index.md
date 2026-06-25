---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/) class.

```python
def __init__(self):
    ...
```

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt

load_options = gw.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    options = gwo_ppt.PresentationWatermarkSlideOptions()
    options.slide_index = 0
    text_wm = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    watermarker.add(text_wm, options)
    watermarker.save("presentation.pptx")
```

### See Also
* class [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/)
