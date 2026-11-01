---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый RotateAngleSearchCriteria с начальным и конечным углом."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Инициализирует новый RotateAngleSearchCriteria с начальным и конечным углом.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| min_angle | `float` | Начальный угол в градусах. |
| max_angle | `float` | Конечный угол в градусах. |

### Пример

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Поиск водяных знаков, повернутых от 30 до 60 градусов
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### См. также
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
