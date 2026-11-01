---
title: "метод rasterize"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Преобразует содержимое страницы в изображение."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Преобразует содержимое страницы в изображение.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Растеризовать первую страницу в PNG‑изображение с разрешением 100 DPI.
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### См. также
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
