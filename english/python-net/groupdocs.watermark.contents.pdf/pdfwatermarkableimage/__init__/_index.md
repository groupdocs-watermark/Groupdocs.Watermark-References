---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new instance of PdfWatermarkableImage using the supplied image data."
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initializes a new instance of [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) using the supplied image data.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | The array of unsigned bytes from which to create the `PdfWatermarkableImage`. |

### Example

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### See Also
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
