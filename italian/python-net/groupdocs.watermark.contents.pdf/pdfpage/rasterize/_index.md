---
title: "metodo rasterize"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Converte il contenuto della pagina in un'immagine."
type: docs
url: /it/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Converte il contenuto della pagina in un'immagine.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| horizontal_resolution | `int` | Risoluzione orizzontale dell'immagine. |
| vertical_resolution | `int` | Risoluzione verticale dell'immagine. |
| image_format | `PdfImageConversionFormat` | Formato immagine. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasterizza la prima pagina in un'immagine PNG a 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Vedi anche
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
