---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initializes a new instance of [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) that closes the output stream when done.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |

### Example

```python
import os
import groupdocs.watermark as gw
import groupdocs.watermark.options as gwo

output_dir = os.path.join(os.getcwd(), "preview")
os.makedirs(output_dir, exist_ok=True)

def create_page_stream(number: int):
    path = os.path.join(output_dir, f"page{number}.png")
    return open(path, "wb")

def release_page_stream(number: int, stream):
    stream.close()

with gw.Watermarker("sample.pdf") as watermarker:
    preview_options = gwo.PreviewOptions(create_page_stream, release_page_stream)
    preview_options.preview_format = gwo.PreviewOptions.PreviewFormats.PNG
    preview_options.page_numbers = [1, 2]
    watermarker.generate_preview(preview_options)
```

## __init__ {#create_page_stream-release_page_stream}

Initializes a new instance of [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) class causing the output stream to be returned to the client for further use.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |
| release_page_stream | `ReleasePageStream` | Notifies that the page preview generation is done and gets the output stream. |

### Example

```python
import os
import groupdocs.watermark as gw
import groupdocs.watermark.options as gwo

output_dir = os.path.join(os.getcwd(), "preview")
os.makedirs(output_dir, exist_ok=True)

def create_page_stream(number: int):
    path = os.path.join(output_dir, f"page{number}.png")
    return open(path, "wb")

def release_page_stream(number: int, stream):
    stream.close()

with gw.Watermarker("sample.pdf") as watermarker:
    preview_options = gwo.PreviewOptions(create_page_stream, release_page_stream)
    preview_options.preview_format = gwo.PreviewOptions.PreviewFormats.PNG
    preview_options.page_numbers = [1, 2]
    watermarker.generate_preview(preview_options)
```

### See Also
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
