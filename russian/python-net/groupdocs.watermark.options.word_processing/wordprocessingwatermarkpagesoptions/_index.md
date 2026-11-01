---
title: "Класс WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры при добавлении водяного знака на страницы документа Word."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/
is_root: false
weight: 110
---


## WordProcessingWatermarkPagesOptions class

Представляет параметры при добавлении водяного знака на страницы документа Word.

Узнать больше:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

Тип WordProcessingWatermarkPagesOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/) | Инициализирует новый экземпляр класса WordProcessingWatermarkPagesOptions. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/page_numbers/) | Номера страниц, на которые будет добавлен водяной знак. |
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
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions, WordProcessingWatermarkPagesOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = WordProcessingLoadOptions()
with Watermarker(r"D:\test.doc", load_options) as watermarker:
    watermark = TextWatermark("text", Font("Arial", 42))
    options = WordProcessingWatermarkPagesOptions()
    options.page_numbers = [1]

    watermarker.add(watermark, options)
    watermarker.save()
```

### См. также
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
