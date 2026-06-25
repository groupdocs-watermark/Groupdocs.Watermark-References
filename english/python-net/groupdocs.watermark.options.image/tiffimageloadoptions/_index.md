---
title: TiffImageLoadOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.image/tiffimageloadoptions/
is_root: false
weight: 80
---


## TiffImageLoadOptions class

Represents image loading options for a TIFF image.

The TiffImageLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/__init__/) | Initializes a new instance of the [`TiffImageLoadOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | The file type, indicating its format (e.g., docx, pdf, xlsx, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | The format family of the document, indicating its type (e.g., Image, Pdf, Spreadsheet, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | The password for opening an encrypted document. (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/default/) | Gets the default value for class. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.image as gwo_img

load_options = gw.TiffImageLoadOptions()
with gw.Watermarker("image.tiff", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))
    options = gwo_img.TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save("image.tiff")
```

### See Also
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
