---
title: "método rasterize"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Convierte el contenido de la página en una imagen."
type: docs
url: /es/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Convierte el contenido de la página en una imagen.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasterizar la primera página a una imagen PNG a 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Ver también
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
