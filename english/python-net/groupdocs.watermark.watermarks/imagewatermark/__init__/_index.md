---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new ImageWatermark instance using the specified file path.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The path to the image that will be used as watermark. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("presentation.pptx") as watermarker:
    with gww.ImageWatermark("watermark.jpg") as watermark:
        watermarker.add(watermark)
        watermarker.save("presentation.pptx")
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
    import groupdocs.watermark as gw
    import groupdocs.watermark.watermarks as gww

    with open("watermark.jpg", "rb") as f:
        data = f.read()

    with gw.Watermarker("image.png") as watermarker:
        with gww.ImageWatermark(io.BytesIO(data)) as watermark:
            watermarker.add(watermark)
            watermarker.save("image.png")
    ```

### See Also
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
