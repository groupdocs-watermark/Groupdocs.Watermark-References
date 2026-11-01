---
title: "PresentationLoadOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Geeft document‑laadopties weer voor een Presentatie‑document."
type: docs
url: /nl/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Geeft document‑laadopties weer voor een Presentatie‑document.

Het PresentationLoadOptions type toont de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Initialiseert een nieuw exemplaar van de PresentationLoadOptions klasse met een opgegeven wachtwoord. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Het type van het bestand, dat het formaat aangeeft (bijv. docx, pdf, xlsx, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | De formaatfamilie van het document, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Het wachtwoord voor het openen van een versleuteld document. (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Haalt de standaardwaarde op voor de klasse. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # werken met het document
    pass
```

### Zie ook
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
