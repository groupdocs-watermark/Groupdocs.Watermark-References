---
title: PreviewOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Provides options to set requirements and stream delegates for preview generation.

The PreviewOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Initializes a new instance of [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) that closes the output stream when done. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initializes a new instance of [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) class causing the output stream to be returned to the client for further use. |

### Properties
| Property | Description |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | The page stream creation delegate. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | The page preview height. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | The array of page numbers to generate previews. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | The preview image format. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | The page preview completion delegate. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | The page preview width. |

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
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
