---
title: "rasterize méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Convertit toutes les pages de contenu en images."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Convertit toutes les pages de contenu en images.

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
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Ajouter un filigrane (optionnel)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasteriser chaque page à 100x100 DPI en images PNG
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Voir aussi
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
