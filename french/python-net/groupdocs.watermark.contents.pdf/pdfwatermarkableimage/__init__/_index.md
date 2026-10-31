---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe PdfWatermarkableImage en utilisant les données d'image spécifiées."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialise une nouvelle instance de la classe [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) en utilisant les données d'image spécifiées.

```python
def __init__(self, image_data):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | Le tableau d'octets non signés à partir duquel créer le `PdfWatermarkableImage`. |

### Exemple

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Voir aussi
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
