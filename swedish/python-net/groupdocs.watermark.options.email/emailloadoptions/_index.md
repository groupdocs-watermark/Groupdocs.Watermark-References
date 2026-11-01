---
title: "EmailLoadOptions-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar dokumentläsningsalternativen för ett e‑postmeddelande."
type: docs
url: /sv/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Representerar dokumentläsningsalternativen för ett e‑postmeddelande.

Typen EmailLoadOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Initierar en ny instans av klassen [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Filens typ, som anger dess format (t.ex. docx, pdf, xlsx, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Formatfamiljen för dokumentet, som anger dess typ (t.ex. Image, Pdf, Spreadsheet, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Lösenordet för att öppna ett krypterat dokument. (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Hämtar standardvärdet för klassen. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # manipulera e-postinnehåll här
    watermarker.save("./output.msg")
```

### Se även
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
