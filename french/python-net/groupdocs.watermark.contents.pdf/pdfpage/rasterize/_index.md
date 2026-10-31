---
title: "rasterize méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Convertit le contenu de la page en image."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Convertit le contenu de la page en image.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| horizontal_resolution | `int` | Résolution d'image horizontale. |
| vertical_resolution | `int` | Résolution d'image verticale. |
| image_format | `PdfImageConversionFormat` | Format d'image. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasteriser la première page en image PNG à 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Voir aussi
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
