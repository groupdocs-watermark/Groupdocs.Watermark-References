---
title: "DiagramShapeWatermarkOptions класс"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры добавления водяного знака при добавлении водяного знака формы в документ Visio."
type: docs
url: /ru/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
is_root: false
weight: 50
---


## DiagramShapeWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении водяного знака формы в документ Visio.

- Add watermarks to diagram documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

Тип DiagramShapeWatermarkOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/__init__/) | Инициализирует новый экземпляр класса [`DiagramShapeWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [placement_type](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placement_type/) | Значение, указывающее, на какие страницы следует добавить водяной знак. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | Свойство указывает, запрещено ли редактирование фигуры в Visio. (унаследовано от [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.diagram import DiagramShapeWatermarkOptions
from groupdocs.watermark.contents.diagram import DiagramWatermarkPlacementType

def add_watermark_to_diagram():
    with Watermarker("./diagram.vsdx") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = DiagramShapeWatermarkOptions()
        options.placement_type = DiagramWatermarkPlacementType.BACKGROUND_PAGES
        watermarker.add(watermark, options)

        watermarker.save("./output.vsdx")
```

### См. также
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
