---
title: "Класс PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры добавления водяного знака при добавлении аннотационного водяного знака в PDF-документ."
type: docs
url: /ru/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении аннотационного водяного знака в PDF-документ.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Тип PdfAnnotationWatermarkOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | Инициализирует новый экземпляр класса [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | Индекс страницы, к которой добавляется водяной знак. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | Значение, указывающее, будет ли аннотация печататься, но не отображаться в приложении для просмотра PDF. |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1 применяет водяной знак ко всем страницам (по умолчанию)
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### См. также
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
