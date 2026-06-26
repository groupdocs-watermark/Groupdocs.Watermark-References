---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new ImageWatermark instance with a specified file path."
type: docs
url: /python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new ImageWatermark instance with a specified file path.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The path to the image that will be used as watermark. |

### Example

```python
from groupdocs.watermark.watermarks import ImageWatermark

# Initialize an image watermark from a file path
watermark = ImageWatermark("logo.png")
```

## __init__ {#stream}

Initializes a new ImageWatermark instance using the provided image stream.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The stream containing the image that will be used as watermark. |

### Example

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

# Load image data into a memory stream
with open("watermark.jpg", "rb") as f:
    data = f.read()

# Create a watermarker for the target document
with Watermarker("document.docx") as watermarker:
    # Initialize the image watermark from the stream
    with ImageWatermark(io.BytesIO(data)) as watermark:
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
```

### See Also
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
