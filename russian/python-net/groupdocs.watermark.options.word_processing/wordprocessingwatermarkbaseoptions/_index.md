---
title: "Класс WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет базовый класс для параметров добавления водяного знака в документ Word."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/
is_root: false
weight: 90
---


## WordProcessingWatermarkBaseOptions class

Представляет базовый класс для параметров добавления водяного знака в документ Word.

Тип WordProcessingWatermarkBaseOptions раскрывает следующие члены:

### Свойства
| Свойство | Описание |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | Описательный (альтернативный) текст, который будет связан с фигурой. |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Эффекты, применяемые к водяному знаку, указываются как экземпляр [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) или [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | Свойство указывает, запрещено ли редактирование формы в Word. |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Тип блокировки водяного знака. |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | Имя фигуры. |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | Пароль, используемый для блокировки водяного знака. |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.options.word_processing import WordProcessingWatermarkSectionOptions, WordProcessingLockType
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected", Font("Arial", 36.0))
    options = WordProcessingWatermarkSectionOptions()
    options.is_locked = True
    options.lock_type = WordProcessingLockType.ALLOW_ONLY_FORM_FIELDS
    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### См. также
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
