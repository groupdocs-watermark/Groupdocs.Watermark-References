---
title: PdfArtifactWatermarkOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents watermark adding options when adding an artifact watermark to a PDF document."
type: docs
url: /python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

Represents watermark adding options when adding an artifact watermark to a PDF document.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

The PdfArtifactWatermarkOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | Initializes a new instance of the [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | The page index to add watermark to. |

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
    watermark = gww.ImageWatermark("icon.png")
    watermark.horizontal_alignment = gwc.HorizontalAlignment.RIGHT
    watermark.vertical_alignment = gwc.VerticalAlignment.BOTTOM

    options = gwo_pdf.PdfArtifactWatermarkOptions()
    options.page_index = -1  # default: all pages

    watermarker.add(watermark, options)
    watermarker.save("document.pdf")
```

### See Also
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
