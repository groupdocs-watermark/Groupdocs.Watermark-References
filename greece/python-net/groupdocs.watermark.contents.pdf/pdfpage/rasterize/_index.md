---
title: "rasterize μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει το περιεχόμενο της σελίδας σε εικόνα."
type: docs
url: /el/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Μετατρέπει το περιεχόμενο της σελίδας σε εικόνα.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| horizontal_resolution | `int` | Οριζόντια ανάλυση εικόνας. |
| vertical_resolution | `int` | Κατακόρυφη ανάλυση εικόνας. |
| image_format | `PdfImageConversionFormat` | Μορφή εικόνας. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Μετατρέψτε την πρώτη σελίδα σε εικόνα PNG με ανάλυση 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Δείτε επίσης
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
