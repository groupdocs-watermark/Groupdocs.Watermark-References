---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса DiagramWatermarkableImage, используя указанные данные изображения."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Инициализирует новый экземпляр класса [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) с использованием указанных данных изображения.

```python
def __init__(self, image_data):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_data | `list[int]` | Массив беззнаковых байтов, из которого создаётся `DiagramWatermarkableImage`. |

### Пример

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### См. также
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
