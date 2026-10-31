---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas WordProcessingImageEffects."
type: docs
url: /id/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari kelas [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.watermark.options.word_processing import WordProcessingImageEffects
from groupdocs.watermark.watermarks import Color

# Buat efek gambar default untuk watermark
effects = WordProcessingImageEffects()
effects.brightness = 0.7
effects.contrast = 0.6
effects.chroma_key = Color.red
```

### Lihat Juga
* class [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/)
