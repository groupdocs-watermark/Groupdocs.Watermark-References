---
title: "Класс TileOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры настройки водяных знаков в режиме плитки."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/tileoptions/
is_root: false
weight: 140
---


## TileOptions class

Представляет параметры настройки водяных знаков в режиме плитки.

Тип TileOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/__init__/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [line_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/line_spacing/) | Расстояние между строками для водяных знаков в режиме плитки. |
| [rotate_around_origin](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/rotate_around_origin/) | Свойство указывает, вращаются ли повторяющиеся водяные знаки вокруг центра документа. |
| [tile_type](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/tile_type/) | Тип выравнивания плитки для водяных знаков. |
| [watermark_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/watermark_spacing/) | Расстояние между сериями для водяных знаков в режиме плитки. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.gray
    watermark.opacity = 0.3
    watermark.rotate_angle = -45.0
    watermark.text_alignment = TextAlignment.CENTER

    line_spacing = MeasureValue()
    line_spacing.measure_type = TileMeasureType.PERCENT
    line_spacing.value = 12.0

    watermark_spacing = MeasureValue()
    watermark_spacing.measure_type = TileMeasureType.PERCENT
    watermark_spacing.value = 10.0

    tile_options = TileOptions()
    tile_options.tile_type = TileType.ONE_THIRD_OFFSET
    tile_options.line_spacing = line_spacing
    tile_options.watermark_spacing = watermark_spacing
    watermark.tile_options = tile_options

    watermarker.add(watermark)
```

### Guides
Руководства задач, использующие `TileOptions`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### См. также
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
