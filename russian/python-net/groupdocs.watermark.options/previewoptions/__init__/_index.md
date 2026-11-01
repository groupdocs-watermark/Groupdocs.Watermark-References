---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр PreviewOptions, который закрывает выходной поток после использования."
type: docs
url: /ru/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Инициализирует новый экземпляр PreviewOptions, который закрывает выходной поток после использования.

```python
def __init__(self, create_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Создаёт поток для предварительного просмотра конкретной страницы. |

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

## __init__ {#create_page_stream-release_page_stream}

Инициализирует новый экземпляр PreviewOptions, который возвращает выходной поток клиенту для дальнейшего использования.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable, который создаёт поток для предварительного просмотра конкретной страницы. Принимает номер страницы (`int`) и должен возвращать записываемый поток (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable, вызываемый после завершения генерации предварительного просмотра страницы и предоставляющий выходной поток. |

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

### См. также
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
