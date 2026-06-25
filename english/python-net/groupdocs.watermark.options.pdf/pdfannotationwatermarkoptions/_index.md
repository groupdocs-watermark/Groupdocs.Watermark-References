---
title: PdfAnnotationWatermarkOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

Represents watermark adding options when adding annotation watermark to a PDF document.

Learn more: Add watermarks to PDF documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents).

The PdfAnnotationWatermarkOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | Initializes a new instance of the [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | The page index to add watermark to. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | The value indicating whether annotation will be printed, but not displayed in PDF viewing applications. |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.pdf as gwo_pdf
import groupdocs.watermark.common as gwc

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    options = gwo_pdf.PdfAnnotationWatermarkOptions()
    options.page_index = -1  # default - all pages

    text_watermark = gww.TextWatermark("Annotation watermark", gww.Font("Arial", 8.0))
    text_watermark.horizontal_alignment = gwc.HorizontalAlignment.LEFT
    text_watermark.vertical_alignment = gwc.VerticalAlignment.TOP
    watermarker.add(text_watermark, options)

    with gww.ImageWatermark("protect.jpg") as image_watermark:
        image_watermark.horizontal_alignment = gwc.HorizontalAlignment.RIGHT
        image_watermark.vertical_alignment = gwc.VerticalAlignment.TOP
        watermarker.add(image_watermark, options)

    watermarker.save("document.pdf")
```

### See Also
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
