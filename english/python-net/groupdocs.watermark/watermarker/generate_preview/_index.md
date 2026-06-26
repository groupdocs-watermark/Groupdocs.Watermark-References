---
title: generate_preview method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Generates preview images for the document."
type: docs
url: /python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Generates preview images for the document.

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Additional options to use when generating preview images. |

### Example

```python
import os
import groupdocs.watermark as gw
import groupdocs.watermark.options as gwo

output_directory = os.path.join(os.getcwd(), "preview")
os.makedirs(output_directory, exist_ok=True)

def create_page_stream(number: int):
    path = os.path.join(output_directory, f"page{number}.png")
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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
