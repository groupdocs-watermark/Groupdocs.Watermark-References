---
title: "метод rasterize"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Преобразует все страницы содержимого в изображения."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Преобразует все страницы содержимого в изображения.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| horizontal_resolution | `int` | Горизонтальное разрешение изображения. |
| vertical_resolution | `int` | Вертикальное разрешение изображения. |
| image_format | `PdfImageConversionFormat` | Формат изображения. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Добавить водяной знак (необязательно)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Растеризовать каждую страницу с разрешением 100x100 DPI в PNG‑изображения
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### См. также
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
