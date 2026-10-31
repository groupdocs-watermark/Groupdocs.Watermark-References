---
title: "Classe EmailLoadOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di caricamento del documento per un messaggio email."
type: docs
url: /it/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Rappresenta le opzioni di caricamento del documento per un messaggio email.

Il tipo EmailLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Inizializza una nuova istanza della classe [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Il tipo di file, che indica il suo formato (ad es., docx, pdf, xlsx, ecc.). (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La famiglia di formato del documento, che indica il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.). (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La password per aprire un documento crittografato. (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Ottiene il valore predefinito per la classe. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # manipola il contenuto dell'email qui
    watermarker.save("./output.msg")
```

### Vedi anche
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
