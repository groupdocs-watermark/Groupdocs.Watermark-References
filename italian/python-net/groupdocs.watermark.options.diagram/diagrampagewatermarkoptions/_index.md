---
title: "DiagramPageWatermarkOptions classe"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di forma a una pagina specifica di un documento Visio."
type: docs
url: /it/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di forma a una pagina specifica di un documento Visio.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

Il tipo DiagramPageWatermarkOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | Inizializza una nuova istanza della classe [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | L'indice della pagina a cui aggiungere la filigrana. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | La proprietà indica se la modifica della forma in Visio è vietata. (ereditata da [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.diagram import DiagramPageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./diagram.vsdx") as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42.0))

    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.vsdx")
```

### Vedi anche
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
