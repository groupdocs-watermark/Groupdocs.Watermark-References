---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe WordProcessingImageEffects."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/).

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.watermark.options.word_processing import WordProcessingImageEffects
from groupdocs.watermark.watermarks import Color

# Crea effetti immagine predefiniti per un watermark
effects = WordProcessingImageEffects()
effects.brightness = 0.7
effects.contrast = 0.6
effects.chroma_key = Color.red
```

### Vedi anche
* class [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/)
