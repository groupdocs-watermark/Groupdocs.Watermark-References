---
title: "rasterize-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Converteert paginainhoud naar een afbeelding."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Converteert paginainhoud naar een afbeelding.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| horizontal_resolution | `int` | Horizontale beeldresolutie. |
| vertical_resolution | `int` | Verticale beeldresolutie. |
| image_format | `PdfImageConversionFormat` | Beeldformaat. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasteriseer de eerste pagina naar een PNG-afbeelding met 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Zie ook
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
