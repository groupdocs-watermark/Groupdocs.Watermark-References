---
title: rasterize method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Converts page content into an image."
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Converts page content into an image.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasterize the first page to a PNG image at 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### See Also
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
