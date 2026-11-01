---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса PresentationPreviewOptions, закрывая поток вывода."
type: docs
url: /ru/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Инициализирует новый экземпляр класса PresentationPreviewOptions, закрывая поток вывода.

```python
def __init__(self, create_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Создаёт поток для предварительного просмотра конкретной страницы. |

## __init__ {#create_page_stream-release_page_stream}

Инициализирует новый экземпляр [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/), возвращая поток вывода клиенту для дальнейшего использования.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Создаёт поток для предварительного просмотра конкретной страницы. |
| release_page_stream | `ReleasePageStream` | Уведомляет, что генерация предварительного просмотра страницы завершена, и получает выходной поток. |

### См. также
* class [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/)
