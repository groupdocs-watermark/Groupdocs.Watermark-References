---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe PdfWatermarkableImage utilizzando i dati immagine specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inizializza una nuova istanza della classe [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) utilizzando i dati immagine specificati.

```python
def __init__(self, image_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_data | `list[int]` | L'array di byte senza segno da cui creare il `PdfWatermarkableImage`. |

### Esempio

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Vedi anche
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
