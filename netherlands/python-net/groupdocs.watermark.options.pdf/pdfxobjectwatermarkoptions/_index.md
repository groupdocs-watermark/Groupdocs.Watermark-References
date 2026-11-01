---
title: "PdfXObjectWatermarkOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt opties voor het toevoegen van een watermerk voor een XObject‑watermerk aan een PDF‑document voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
is_root: false
weight: 70
---


## PdfXObjectWatermarkOptions class

Stelt opties voor het toevoegen van een watermerk voor een XObject‑watermerk aan een PDF‑document voor.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Het PdfXObjectWatermarkOptions‑type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`PdfXObjectWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/page_index/) | De paginanaam (index) waarop het watermerk moet worden toegevoegd. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfXObjectWatermarkOptions
from groupdocs.watermark.watermarks import ImageWatermark

load_options = PdfLoadOptions()
with Watermarker("./document.pdf", load_options) as watermarker:
    with ImageWatermark("./logo.png") as watermark:
        options = PdfXObjectWatermarkOptions()
        options.page_index = 0  # apply to the first page
        watermarker.add(watermark, options)
    watermarker.save("./output.pdf")
```

### Zie ook
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
