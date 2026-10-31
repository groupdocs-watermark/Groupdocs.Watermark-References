---
title: "rasterize μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει όλες τις σελίδες περιεχομένου σε εικόνες."
type: docs
url: /el/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Μετατρέπει όλες τις σελίδες περιεχομένου σε εικόνες.

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
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Προσθήκη υδατογραφήματος (προαιρετικό)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterize κάθε σελίδα σε 100x100 DPI σε εικόνες PNG
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Δείτε επίσης
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
