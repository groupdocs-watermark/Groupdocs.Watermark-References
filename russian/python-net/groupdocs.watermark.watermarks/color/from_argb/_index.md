---
title: "from_argb метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Создаёт структуру Color из 32‑битного значения ARGB."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Создаёт структуру Color из 32‑битного значения ARGB.

```python
def from_argb(cls, argb):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb | `int` | Значение, указывающее 32‑битное значение ARGB. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Создаёт структуру Color из указанного базового Color, но с новым значением альфа.

Хотя этот метод позволяет передать 32‑битное значение для альфа‑канала, значение ограничено 8 битами.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| alpha | `int` | Альфа‑значение для нового Color. Допустимые значения от 0 до 255. |
| base_color | `Color` | Color, из которого создаётся новый Color. |

**Returns:** Color: The Color that this method creates.

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Альфа‑значение меньше 0 или больше 255. |

### Пример

```python
from groupdocs.watermark.watermarks import Color

# Создать полупрозрачный красный цвет (альфа 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Создаёт [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) из указанных 8‑битных значений красного, зелёного и синего, при этом альфа‑канал неявно устанавливается в 255 (полностью непрозрачный).

Хотя этот метод позволяет передать 32‑битное значение для каждой цветовой компоненты, каждая компонента ограничена 8 битами.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| red | `int` | Значение красной компоненты для нового `Color`. Допустимые значения от 0 до 255. |
| green | `int` | Значение зелёной компоненты для нового `Color`. Допустимые значения от 0 до 255. |
| blue | `int` | Значение синей компоненты для нового `Color`. Допустимые значения от 0 до 255. |

**Returns:** Color: The color that this method creates.

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Красный, зелёный или синий компонент меньше 0 или больше 255. |

## from_argb {#alpha-red-green-blue}

Создаёт [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) из четырёх значений компонентов ARGB (альфа, красный, зелёный и синий).

Хотя этот метод позволяет передать 32‑битное значение для каждой компоненты, значение каждой компоненты ограничено 8 битами.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| alpha | `int` | Значение альфа‑компоненты для нового `Color`. Допустимые значения от 0 до 255. |
| red | `int` | Значение красной компоненты для нового `Color`. Допустимые значения от 0 до 255. |
| green | `int` | Значение зелёной компоненты для нового `Color`. Допустимые значения от 0 до 255. |
| blue | `int` | Значение синей компоненты для нового `Color`. Допустимые значения от 0 до 255. |

**Returns:** Color: The `Color` that this method creates.

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Красный, зелёный или синий компонент меньше 0 или больше 255. |

### Пример

```python
from groupdocs.watermark.watermarks import Color

# Создать полностью непрозрачный красный цвет
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### См. также
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
