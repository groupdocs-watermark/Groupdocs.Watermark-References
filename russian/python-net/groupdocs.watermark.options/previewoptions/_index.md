---
title: "Класс PreviewOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра."
type: docs
url: /ru/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра.

Тип PreviewOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Инициализирует новый экземпляр PreviewOptions, который закрывает выходной поток после использования. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Инициализирует новый экземпляр PreviewOptions, который возвращает выходной поток клиенту для дальнейшего использования. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Делегат создания потока страницы, используемый для получения записываемого потока для каждой отрисованной страницы. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Высота предварительного просмотра страницы. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Массив номеров страниц для генерации предварительных просмотров. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Формат изображения предварительного просмотра. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Делегат завершения предварительного просмотра страницы. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Ширина предварительного просмотра страницы. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Предоставьте поток записываемого файла для каждой страницы, которую нужно отобразить
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
Руководства задач, использующие `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### См. также
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
