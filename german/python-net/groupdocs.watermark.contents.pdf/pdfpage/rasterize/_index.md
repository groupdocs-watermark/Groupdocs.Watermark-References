---
title: "rasterize Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Konvertiert den Seiteninhalt in ein Bild."
type: docs
url: /de/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Konvertiert den Seiteninhalt in ein Bild.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasterisiere die erste Seite zu einem PNG-Bild bei 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Siehe auch
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
