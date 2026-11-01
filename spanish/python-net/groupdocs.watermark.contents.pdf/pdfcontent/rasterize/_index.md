---
title: "método rasterize"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Convierte todas las páginas de contenido en imágenes."
type: docs
url: /es/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Convierte todas las páginas de contenido en imágenes.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| horizontal_resolution | `int` | Resolución horizontal de la imagen. |
| vertical_resolution | `int` | Resolución vertical de la imagen. |
| image_format | `PdfImageConversionFormat` | Formato de imagen. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Agregar una marca de agua (opcional)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterizar cada página a 100x100 DPI en imágenes PNG
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Ver también
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
