---
title: "Класс ImageWatermark"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет изображение водяного знака."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Представляет изображение водяного знака.

Узнать больше:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

Тип ImageWatermark раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Инициализирует новый экземпляр ImageWatermark с указанным путём к файлу. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Инициализирует новый ImageWatermark с предоставленным потоком изображения. |

### Методы
| Метод | Описание |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Освобождает текущий экземпляр. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | Свойство, указывающее, учитываются ли при расчете размер и координаты водяного знака с учетом отступов родителя. Если установлено в True, расчеты учитывают отступы родителя; по умолчанию значение False и отступы родителя игнорируются. (наследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | Желаемая высота этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (наследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | Горизонтальное выравнивание этого Watermark. (наследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | Свойство, указывающее, должен ли водяной знак располагаться в фоне. Если true, водяной знак размещается внизу; иначе — вверху (по умолчанию False). (наследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Настройки отступов этого Watermark. (наследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | Непрозрачность этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Настройки разметки страниц этого Watermark. (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | Угол поворота этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) в градусах. (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | Свойство указывает, следует ли сохранять информацию о добавленных водяных знаках в метаданных документа. (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Коэффициент масштабирования этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), определяющий, как размер водяного знака зависит от размера родителя. (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Тип масштабирования водяного знака. (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Параметры для определения повторяющегося водяного знака. (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | Вертикальное выравнивание этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | Желаемая ширина этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | Координата x этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | Координата y этого [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (унаследовано от [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Пример

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Загрузить данные изображения в поток
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Открыть документ и добавить водяной знак изображения
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Руководства задач, использующие `ImageWatermark`:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### См. также
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
