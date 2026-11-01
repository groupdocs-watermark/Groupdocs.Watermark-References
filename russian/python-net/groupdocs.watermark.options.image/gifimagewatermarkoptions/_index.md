---
title: "Класс GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры добавления водяного знака при добавлении водяного знака к GIF‑изображению."
type: docs
url: /ru/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
is_root: false
weight: 30
---


## GifImageWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении водяного знака к GIF‑изображению.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Тип GifImageWatermarkOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/) | Создаёт новый экземпляр класса [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) . |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/#frame_index) | Создаёт новый экземпляр класса [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) с указанным индексом кадра. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | Индекс кадра, к которому добавляется водяной знак. (наследовано от [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import GifImageLoadOptions, GifImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = GifImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))

    options = GifImageWatermarkOptions()
    options.frame_index = 0

    watermarker.add(watermark, options)
    watermarker.save()
```

### См. также
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
