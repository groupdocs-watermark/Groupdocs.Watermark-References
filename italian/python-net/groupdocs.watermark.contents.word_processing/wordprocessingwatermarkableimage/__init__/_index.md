---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe WordProcessingWatermarkableImage utilizzando i dati immagine specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inizializza una nuova istanza della classe [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) utilizzando i dati immagine specificati.

```python
def __init__(self, image_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_data | `list[int]` | L'array di byte senza segno da cui creare il `WordProcessingWatermarkableImage`. |

### Esempio

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Vedi anche
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
