---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe PresentationWatermarkableImage utilizzando i dati immagine specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inizializza una nuova istanza della classe [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) utilizzando i dati immagine specificati.

```python
def __init__(self, image_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_data | `list[int]` | L'array di byte senza segno da cui creare il `PresentationWatermarkableImage`. |

### Esempio

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Vedi anche
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
