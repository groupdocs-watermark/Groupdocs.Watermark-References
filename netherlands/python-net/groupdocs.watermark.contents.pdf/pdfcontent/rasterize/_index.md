---
title: "rasterize-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Converteert alle inhoudspagina's naar afbeeldingen."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Converteert alle inhoudspagina's naar afbeeldingen.

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
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Voeg een watermerk toe (optioneel)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasteriseer elke pagina op 100x100 DPI naar PNG-afbeeldingen
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Zie ook
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
