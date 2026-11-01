---
title: "Класс WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры при добавлении фигурного водяного знака в раздел документа Word."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/
is_root: false
weight: 120
---


## WordProcessingWatermarkSectionOptions class

Представляет параметры при добавлении фигурного водяного знака в раздел документа Word.

Узнать больше:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

Тип WordProcessingWatermarkSectionOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/__init__/) | Инициализирует новый экземпляр класса [`WordProcessingWatermarkSectionOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [section_index](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/section_index/) | Индекс раздела, к которому будет добавлен водяной знак. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | Описательный (альтернативный) текст, который будет связан с фигурой. (унаследовано от [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Эффекты, применяемые к водяному знаку, указанные как экземпляр [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) или [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). (унаследовано от [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | Свойство указывает, запрещено ли редактирование фигуры в Word. (унаследовано от [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Тип блокировки водяного знака. (унаследовано от [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | Имя фигуры. (унаследовано от [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | Пароль, используемый для блокировки водяного знака. (унаследовано от [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions,
)

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER
    watermark.foreground_color = Color.red

    options = WordProcessingWatermarkSectionOptions()
    options.section_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### См. также
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
