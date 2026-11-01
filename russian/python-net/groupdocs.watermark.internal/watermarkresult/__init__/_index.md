---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса WatermarkResult."
type: docs
url: /ru/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/).

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Инициализирует новый экземпляр WatermarkResult со специфическими значениями.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_document_size | `int` | Размер исходного документа в байтах. |
| processing_time | `timedelta` | Время обработки в миллисекундах. |
| final_document_size | `int` | Размер окончательного обработанного документа в байтах. |
| number_watermarks_applied | `int` | Общее количество водяных знаков, применённых к документу. |

### См. также
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
