---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый TextWatermark с указанным текстом и шрифтом."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Инициализирует новый TextWatermark с указанным текстом и шрифтом.

```python
def __init__(self, text, font):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст, используемый в качестве водяного знака. |
| font | `Font` | Шрифт текста. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### См. также
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
