---
title: "Класс PresentationWatermarkNoteSlideOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры при добавлении водяного знака на слайд заметок документа Presentation."
type: docs
url: /ru/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/
is_root: false
weight: 120
---


## PresentationWatermarkNoteSlideOptions class

Представляет параметры при добавлении водяного знака на слайд заметок документа Presentation.

Узнать больше:
- [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

Смотрите примеры использования в [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Тип PresentationWatermarkNoteSlideOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/__init__/) | Инициализирует новый экземпляр класса [`PresentationWatermarkNoteSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/slide_index/) | Индекс слайда, к заметке которого будет добавлен водяной знак. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Описательный (альтернативный) текст, который будет связан с фигурой. (унаследовано от [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Эффекты, применяемые к водяному знаку, указанные как экземпляр [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) или [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). (унаследовано от [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | Свойство указывает, запрещено ли редактирование фигуры в PowerPoint. (унаследовано от [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Имя фигуры. (унаследовано от [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | Свойство, указывающее, смешаны ли символы текстового водяного знака с нечитаемыми символами. (унаследовано от [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    content = watermarker.get_content()

    note_opts = gwo_ppt.PresentationWatermarkNoteSlideOptions()
    note_opts.slide_index = 0  # index of the slide whose notes will receive the watermark
    watermarker.add(watermark, note_opts)
```

### См. также
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
