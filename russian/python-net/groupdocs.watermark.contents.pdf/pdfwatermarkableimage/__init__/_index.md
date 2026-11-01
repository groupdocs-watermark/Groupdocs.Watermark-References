---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса PdfWatermarkableImage, используя указанные данные изображения."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Инициализирует новый экземпляр класса [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) с использованием указанных данных изображения.

```python
def __init__(self, image_data):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_data | `list[int]` | Массив беззнаковых байтов, из которого создаётся `PdfWatermarkableImage`. |

### Пример

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### См. также
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
