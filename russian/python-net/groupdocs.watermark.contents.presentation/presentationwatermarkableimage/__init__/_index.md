---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса PresentationWatermarkableImage, используя указанные данные изображения."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Инициализирует новый экземпляр класса [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) с использованием указанных данных изображения.

```python
def __init__(self, image_data):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_data | `list[int]` | Массив беззнаковых байтов, из которого создаётся `PresentationWatermarkableImage`. |

### Пример

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### См. также
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
