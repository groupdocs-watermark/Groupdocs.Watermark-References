---
title: "метод get_images"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Находит изображения в соответствии с указанными критериями поиска."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Находит изображения в соответствии с указанными критериями поиска.

Поиск выполняется в объектах, указанных в [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Узнайте больше о поиске водяных знаков https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Критерии поиска для использования. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType

with Watermarker("./document.pdf") as watermarker:
    watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
    watermark.foreground_color = Color.red
    watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS

    for image in watermarker.get_images():
        if image.width > 100 and image.height > 100:
            image.add(watermark)

    watermarker.save("./output.pdf")
```

## get_images

Находит все изображения в документе.

Поиск выполняется в объектах, указанных в [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Узнайте больше о поиске водяных знаков по адресу https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # Каждое растровое изображение, встроенное в документ
        for image in watermarker.get_images():
            # Пропускать маленькие изображения, такие как значки или маркеры
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
