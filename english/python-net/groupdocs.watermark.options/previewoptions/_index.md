---
title: PreviewOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Provides options to set requirements and stream delegates for preview generation."
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
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Initializes a new PreviewOptions instance that closes the output stream after use. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initializes a new PreviewOptions instance that returns the output stream to the client for further use. |

### Properties
| Property | Description |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | The page stream creation delegate used to obtain a writable stream for each rendered page. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | The page preview height. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | The array of page numbers to generate previews. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | The preview image format. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | The page preview completion delegate. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | The page preview width. |

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Supply a writable file stream for each page to render
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
Task guides that use `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### See Also
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
