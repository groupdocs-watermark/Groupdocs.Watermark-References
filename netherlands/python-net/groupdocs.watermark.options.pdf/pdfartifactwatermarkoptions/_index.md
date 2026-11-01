---
title: "PdfArtifactWatermarkOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt opties voor het toevoegen van een watermerk voor een artefactwatermerk aan een PDF‑document voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

Stelt opties voor het toevoegen van een watermerk voor een artefactwatermerk aan een PDF‑document voor.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Het PdfArtifactWatermarkOptions‑type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | De paginanaam (index) waarop het watermerk moet worden toegevoegd. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfArtifactWatermarkOptions

with Watermarker("./test.pdf", PdfLoadOptions()) as watermarker:
    with ImageWatermark("./icon.png") as watermark:
        watermark.horizontal_alignment = HorizontalAlignment.RIGHT
        watermark.vertical_alignment = VerticalAlignment.BOTTOM
        options = PdfArtifactWatermarkOptions()
        options.page_index = -1  # default: all pages
        watermarker.add(watermark, options)
        watermarker.save()
```

### Zie ook
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
