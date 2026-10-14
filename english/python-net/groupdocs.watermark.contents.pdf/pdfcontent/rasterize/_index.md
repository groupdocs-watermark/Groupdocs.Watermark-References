---
title: rasterize method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Converts all content pages into images."
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Converts all content pages into images.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| horizontal_resolution | `int` | Horizontal image resolution. |
| vertical_resolution | `int` | Vertical image resolution. |
| image_format | `PdfImageConversionFormat` | Image format. |

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Add a watermark (optional)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterize every page at 100x100 DPI to PNG images
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### See Also
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
