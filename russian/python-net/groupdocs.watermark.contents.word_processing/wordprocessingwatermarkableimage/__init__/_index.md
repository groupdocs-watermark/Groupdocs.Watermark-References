---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса WordProcessingWatermarkableImage, используя указанные данные изображения."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Инициализирует новый экземпляр класса [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) с использованием указанных данных изображения.

```python
def __init__(self, image_data):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_data | `list[int]` | Массив беззнаковых байтов, из которого создаётся `WordProcessingWatermarkableImage`. |

### Пример

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### См. также
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
