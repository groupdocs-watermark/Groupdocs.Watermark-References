---
title: "Класс MeasureValue"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет измеряемое значение с определённым типом и числовым значением."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Представляет измеряемое значение с определённым типом и числовым значением.

Тип MeasureValue раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Тип измерения. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Числовое значение измерения; оно должно быть больше 0. |

### Пример

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Создать измерение, выраженное в процентах от страницы
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Руководства задач, использующие `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### См. также
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
