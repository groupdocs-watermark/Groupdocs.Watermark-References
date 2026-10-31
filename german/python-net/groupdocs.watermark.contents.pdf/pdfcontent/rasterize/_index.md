---
title: "rasterize Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Konvertiert alle Inhaltsseiten in Bilder."
type: docs
url: /de/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Konvertiert alle Inhaltsseiten in Bilder.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| horizontal_resolution | `int` | Horizontale Bildauflösung. |
| vertical_resolution | `int` | Vertikale Bildauflösung. |
| image_format | `PdfImageConversionFormat` | Bildformat. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Ein Wasserzeichen hinzufügen (optional)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterisiere jede Seite mit 100x100 DPI zu PNG-Bildern
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Siehe auch
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
