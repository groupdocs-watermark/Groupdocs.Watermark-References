---
title: "Класс ColorRange"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет диапазон цветов, использующий представление HSB цвета RGB."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Представляет диапазон цветов, использующий представление HSB цвета RGB.

Тип ColorRange раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Инициализирует новый экземпляр класса [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/). |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Инициализирует новый экземпляр [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) с указанным точным цветом. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Флаг, указывающий, находится ли только пустой цвет в диапазоне. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Конечное значение яркости, в диапазоне от 0.0 (чёрный) до 1.0 (белый). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Конечное значение оттенка, в градусах. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Конечное значение насыщенности. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Начальное значение яркости, в диапазоне от 0.0 (чёрный) до 1.0 (белый). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Начальное значение оттенка, в градусах. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Начальное значение насыщенности. |

### Пример

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Создать диапазон цветов для сопоставления цвета переднего плана
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Руководства задач, использующие `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### См. также
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
