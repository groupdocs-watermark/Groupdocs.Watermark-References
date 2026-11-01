---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса WordProcessingImageEffects."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/).

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.watermark.options.word_processing import WordProcessingImageEffects
from groupdocs.watermark.watermarks import Color

# Создать эффекты изображения по умолчанию для водяного знака
effects = WordProcessingImageEffects()
effects.brightness = 0.7
effects.contrast = 0.6
effects.chroma_key = Color.red
```

### См. также
* class [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/)
