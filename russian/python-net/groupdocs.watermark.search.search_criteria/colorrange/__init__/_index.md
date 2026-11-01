---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса ColorRange."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/).

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Создать диапазон цветов по умолчанию
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Инициализирует новый экземпляр [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) с указанным точным цветом.

```python
def __init__(self, exact_color):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| exact_color | `Color` | Точный цвет, из которого создаётся диапазон. |

### См. также
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
