---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Создаёт новый экземпляр класса PdfPreviewOptions, закрывая поток вывода."
type: docs
url: /ru/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Инициализирует новый экземпляр класса [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/), вызывая закрытие выходного потока.

```python
def __init__(self, create_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Создаёт поток для предварительного просмотра конкретной страницы. |

## __init__ {#create_page_stream-release_page_stream}

Инициализирует новый экземпляр PdfPreviewOptions, который возвращает выходной поток клиенту для дальнейшего использования.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Создаёт поток для предварительного просмотра конкретной страницы. |
| release_page_stream | `ReleasePageStream` | Уведомляет, что генерация предварительного просмотра страницы завершена, и получает выходной поток. |

### См. также
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
