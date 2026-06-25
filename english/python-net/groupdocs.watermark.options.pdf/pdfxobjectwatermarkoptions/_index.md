---
title: PdfXObjectWatermarkOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
is_root: false
weight: 70
---


## PdfXObjectWatermarkOptions class

Represents watermark adding options when adding XObject watermark to a pdf document.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

The PdfXObjectWatermarkOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/__init__/) | Initializes a new instance of the [`PdfXObjectWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/page_index/) | The page index to add the watermark to. |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
from groupdocs.watermark import Watermarker, ImageWatermark, PdfLoadOptions, PdfXObjectWatermarkOptions

load_options = PdfLoadOptions()
with Watermarker(r"C:\doc.pdf", load_options) as watermarker:
    watermark = ImageWatermark(r"C:\watermark.png")
    options = PdfXObjectWatermarkOptions()
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save()
```

### See Also
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
