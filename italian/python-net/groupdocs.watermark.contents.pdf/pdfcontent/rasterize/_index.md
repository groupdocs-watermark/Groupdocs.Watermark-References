---
title: "metodo rasterize"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Converte tutte le pagine del contenuto in immagini."
type: docs
url: /it/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Converte tutte le pagine del contenuto in immagini.

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
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Aggiungi una filigrana (opzionale)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterizza ogni pagina a 100x100 DPI in immagini PNG
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Vedi anche
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
