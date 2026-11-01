---
title: "PresentationLoadOptions‑klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar alternativ för dokumentladdning för ett Presentation‑dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Representerar alternativ för dokumentladdning för ett Presentation‑dokument.

PresentationLoadOptions‑typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Initierar en ny instans av [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) klassen. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Initierar en ny instans av PresentationLoadOptions‑klassen med ett angivet lösenord. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Filens typ, som anger dess format (t.ex. docx, pdf, xlsx, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Formatfamiljen för dokumentet, som anger dess typ (t.ex. Image, Pdf, Spreadsheet, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Lösenordet för att öppna ett krypterat dokument. (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Hämtar standardvärdet för klassen. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # arbeta med dokumentet
    pass
```

### Se även
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
