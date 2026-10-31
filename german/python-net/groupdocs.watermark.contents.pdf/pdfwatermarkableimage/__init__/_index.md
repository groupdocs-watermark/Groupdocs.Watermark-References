---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der PdfWatermarkableImage Klasse mit den angegebenen Bilddaten."
type: docs
url: /de/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialisiert eine neue Instanz der [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) Klasse mit den angegebenen Bilddaten.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_data | `list[int]` | Das Array aus unsigned Bytes, aus dem das `PdfWatermarkableImage` erstellt wird. |

### Beispiel

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Siehe auch
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
