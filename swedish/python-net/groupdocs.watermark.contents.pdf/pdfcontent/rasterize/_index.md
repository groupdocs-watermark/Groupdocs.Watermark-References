---
title: "rasterize metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Konverterar alla innehållssidor till bilder."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Konverterar alla innehållssidor till bilder.

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
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Lägg till ett vattenmärke (valfritt)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterisera varje sida vid 100x100 DPI till PNG-bilder
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Se även
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
