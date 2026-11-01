---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует ImageWatermarkResult с уникальным идентификатором водяного знака, полученным после процесса поиска."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks.results/imagewatermarkresult/__init__/
is_root: false
weight: 10
---


## __init__ {#watermark_id}

Инициализирует ImageWatermarkResult уникальным идентификатором водяного знака, полученным после процесса поиска. Этот идентификатор используется для получения дополнительных свойств водяного знака из слоя информации о водяных знаках документа.

```python
def __init__(self, watermark_id):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| watermark_id | `str` | Уникальный идентификатор водяного знака, полученный методом `Sign` или `Search` из `GroupDocs.Signature.Signature`. |

### См. также
* class [`ImageWatermarkResult`](/watermark/python-net/groupdocs.watermark.watermarks.results/imagewatermarkresult/)
