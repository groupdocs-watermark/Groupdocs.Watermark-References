---
title: "EmailLoadOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt de documentlaadopties voor een e-mailbericht voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Stelt de documentlaadopties voor een e-mailbericht voor.

Het type EmailLoadOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Het type van het bestand, dat het formaat aangeeft (bijv. docx, pdf, xlsx, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | De formaatfamilie van het document, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Het wachtwoord voor het openen van een versleuteld document. (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Haalt de standaardwaarde op voor de klasse. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # bewerk e-mailinhoud hier
    watermarker.save("./output.msg")
```

### Zie ook
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
