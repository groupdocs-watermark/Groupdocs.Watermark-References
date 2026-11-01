---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр Thickness с конкретными длинами, применёнными к каждой стороне прямоугольника."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/thickness/__init__/
is_root: false
weight: 10
---


## __init__ {#left-right-top-bottom}

Инициализирует новый экземпляр Thickness с конкретными длинами, применёнными к каждой стороне прямоугольника.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| left | `float` | Толщина левой стороны прямоугольника. |
| right | `float` | Толщина правой стороны прямоугольника. |
| top | `float` | Толщина верхней стороны прямоугольника. |
| bottom | `float` | Толщина нижней стороны прямоугольника. |

## __init__ {#uniform_length}

Инициализирует новый экземпляр Thickness с указанной одинаковой длиной на каждой стороне.

```python
def __init__(self, uniform_length):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| uniform_length | `float` | Единая длина, применяемая ко всем четырём сторонам ограничивающего прямоугольника. |

### См. также
* class [`Thickness`](/watermark/python-net/groupdocs.watermark.watermarks/thickness/)
