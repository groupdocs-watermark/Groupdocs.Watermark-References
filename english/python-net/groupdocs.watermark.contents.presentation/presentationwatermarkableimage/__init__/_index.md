---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new instance of the PresentationWatermarkableImage class using specified image data."
type: docs
url: /python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initializes a new instance of the PresentationWatermarkableImage class using specified image data.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | The array of unsigned bytes from which to create the PresentationWatermarkableImage. |

### Example

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### See Also
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
