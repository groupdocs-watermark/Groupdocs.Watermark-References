---
title: "add метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Добавляет водяной знак в загруженный документ."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Добавляет водяной знак в загруженный документ.

Узнайте больше о добавлении водяных знаков в документации GroupDocs.

```python
def add(self, watermark):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| watermark | `Watermark` | Водяной знак, который будет добавлен в документ. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

Добавляет водяной знак в загруженный документ, используя параметры водяного знака.

Узнайте больше о добавлении водяных знаков: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| watermark | `Watermark` | Водяной знак, который будет добавлен в документ. |
| options | `WatermarkOptions` | Дополнительные параметры, используемые при добавлении водяного знака. |

**Returns:** None.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
