---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase WordProcessingImageEffects."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.watermark.options.word_processing import WordProcessingImageEffects
from groupdocs.watermark.watermarks import Color

# Crear efectos de imagen predeterminados para una marca de agua
effects = WordProcessingImageEffects()
effects.brightness = 0.7
effects.contrast = 0.6
effects.chroma_key = Color.red
```

### Ver también
* class [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/)
