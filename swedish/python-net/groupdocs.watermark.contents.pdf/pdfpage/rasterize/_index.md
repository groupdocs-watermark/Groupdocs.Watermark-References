---
title: "rasterize metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Konverterar sidinnehåll till en bild."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Konverterar sidinnehåll till en bild.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| horizontal_resolution | `int` | Horisontell bildupplösning. |
| vertical_resolution | `int` | Vertikal bildupplösning. |
| image_format | `PdfImageConversionFormat` | Bildformat. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasterisera den första sidan till en PNG-bild med 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Se även
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
