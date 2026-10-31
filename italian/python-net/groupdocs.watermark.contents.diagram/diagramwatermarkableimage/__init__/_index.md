---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe DiagramWatermarkableImage utilizzando i dati immagine specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inizializza una nuova istanza della classe [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) utilizzando i dati immagine specificati.

```python
def __init__(self, image_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_data | `list[int]` | L'array di byte senza segno da cui creare il `DiagramWatermarkableImage`. |

### Esempio

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Vedi anche
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
