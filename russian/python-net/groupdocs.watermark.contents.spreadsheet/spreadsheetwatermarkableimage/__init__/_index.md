---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса SpreadsheetWatermarkableImage, используя указанные данные изображения."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Инициализирует новый экземпляр класса [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) с использованием указанных данных изображения.

```python
def __init__(self, image_data):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_data | `list[int]` | Массив беззнаковых байтов, из которого создаётся `SpreadsheetWatermarkableImage`. |

### Пример

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### См. также
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
