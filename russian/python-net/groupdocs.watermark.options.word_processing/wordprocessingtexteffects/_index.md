---
title: "Класс WordProcessingTextEffects"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет эффекты, которые могут быть применены к текстовому водяному знаку в документе Word."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/
is_root: false
weight: 80
---


## WordProcessingTextEffects class

Представляет эффекты, которые могут быть применены к текстовому водяному знаку в документе Word.

Тип WordProcessingTextEffects раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/__init__/) | Инициализирует новый экземпляр класса [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [flip_orientation](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/flip_orientation/) | Ориентация фигуры. |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | Настройки формата линии, представленные экземпляром [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (наследовано от [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/default/) | Получает значение по умолчанию для класса. |

### Пример

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.word_processing as gwo_wp
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_wp.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))

    effects = gwo_wp.WordProcessingTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1

    options = gwo_wp.WordProcessingWatermarkSectionOptions()
    options.effects = effects

    watermarker.add(watermark, options)
    watermarker.save("output.docx")
```

### См. также
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
