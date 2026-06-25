---
title: rasterize method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
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

**Returns:** None.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwc

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    watermark = gww.TextWatermark("Do not copy", gww.Font("Arial", 8.0))
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER
    watermark.vertical_alignment = gwc.VerticalAlignment.CENTER
    watermark.rotate_angle = 45
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 1.0
    watermark.opacity = 0.5

    watermarker.add(watermark)
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    pdf_content.rasterize(100, 100, gwc_pdf.PdfImageConversionFormat.PNG)
    watermarker.save("document.pdf")
```

### See Also
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
