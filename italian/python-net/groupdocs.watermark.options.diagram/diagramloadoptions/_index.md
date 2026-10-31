---
title: "DiagramLoadOptions classe"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di caricamento del documento per un documento Visio."
type: docs
url: /it/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Rappresenta le opzioni di caricamento del documento per un documento Visio.

Il tipo DiagramLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | Inizializza una nuova istanza della classe [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | Inizializza una nuova istanza della classe [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) con una password specificata. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Il tipo di file, che indica il suo formato (ad es., docx, pdf, xlsx, ecc.). (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La famiglia di formato del documento, che indica il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.). (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La password per aprire un documento crittografato. (eredita da [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | Ottiene il valore predefinito per la classe. |

### Esempio

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    # manipola le forme qui
    watermarker.save("output.vsdx")
```

### Vedi anche
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
