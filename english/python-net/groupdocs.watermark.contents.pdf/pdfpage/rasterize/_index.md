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
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwc
import groupdocs.watermark.options.pdf as gwo_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    watermark = gww.TextWatermark("Do not copy", gww.Font("Arial", 8.0))
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER
    watermark.vertical_alignment = gwc.VerticalAlignment.CENTER
    watermark.rotate_angle = 45
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 1.0
    watermark.opacity = 0.5

    options = gwo_pdf.PdfArtifactWatermarkOptions()
    options.page_index = 0
    watermarker.add(watermark, options)

    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    pdf_content.pages[0].rasterize(100, 100, gwc_pdf.PdfImageConversionFormat.PNG)
    watermarker.save("document.pdf")
```

### See Also
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
