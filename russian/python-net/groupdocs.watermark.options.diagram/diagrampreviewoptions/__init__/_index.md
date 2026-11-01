---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Создаёт новый экземпляр класса DiagramPreviewOptions, закрывая выходной поток."
type: docs
url: /ru/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Инициализирует новый экземпляр класса [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/), закрывая выходной поток.

```python
def __init__(self, create_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Создаёт поток для предварительного просмотра конкретной страницы. |

## __init__ {#create_page_stream-release_page_stream}

Инициализирует новый экземпляр [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/), возвращая выходной поток клиенту для дальнейшего использования.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Создаёт поток для предварительного просмотра конкретной страницы. |
| release_page_stream | `ReleasePageStream` | Уведомляет, что генерация предварительного просмотра страницы завершена, и получает выходной поток. |

### См. также
* class [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/)
