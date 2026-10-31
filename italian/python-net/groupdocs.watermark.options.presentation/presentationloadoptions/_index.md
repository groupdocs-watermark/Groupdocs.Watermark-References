---
title: "Classe PresentationLoadOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di caricamento del documento per un documento Presentation."
type: docs
url: /it/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Rappresenta le opzioni di caricamento del documento per un documento Presentation.

Il tipo PresentationLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Inizializza una nuova istanza della classe [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Inizializza una nuova istanza della classe PresentationLoadOptions con una password specificata. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Il tipo di file, che indica il suo formato (ad es., docx, pdf, xlsx, ecc.). (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La famiglia di formato del documento, che indica il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.). (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La password per aprire un documento crittografato. (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Ottiene il valore predefinito per la classe. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # lavorare con il documento
    pass
```

### Vedi anche
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
