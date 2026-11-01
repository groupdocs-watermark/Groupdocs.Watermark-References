---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av PdfWatermarkableImage-klassen med angivna bilddata."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initierar en ny instans av klassen [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) med angivna bilddata.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_data | `list[int]` | Arrayen av osignerade byte som används för att skapa `PdfWatermarkableImage`. |

### Exempel

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Se även
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
