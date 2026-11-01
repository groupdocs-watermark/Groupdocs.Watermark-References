---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de PdfWatermarkableImage-klasse met opgegeven beeldgegevens."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialiseert een nieuw exemplaar van de [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) klasse met gespecificeerde afbeeldingsgegevens.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_data | `list[int]` | De array van unsigned bytes waaruit de `PdfWatermarkableImage` wordt gemaakt. |

### Voorbeeld

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Zie ook
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
