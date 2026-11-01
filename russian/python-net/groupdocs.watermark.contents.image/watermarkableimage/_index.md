---
title: "Класс WatermarkableImage"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет изображение внутри документа."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Представляет изображение внутри документа.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

Тип WatermarkableImage раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Добавляет водяной знак к этому [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Этот метод предполагает, что смещение и размер водяного знака измеряются в пикселях (если они заданы). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Получает изображение в виде массива байтов. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Находит изображения в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется по объектам, перечисленным в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Высота этого [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) в пикселях. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Ширина этого WatermarkableImage в пикселях. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Инициализировать текстовый водяной знак.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Найти все изображения в документе.
    images = watermarker.get_images()

    # Добавить водяной знак к каждому изображению.
    for img in images:
        img.add(watermark)

    # Сохранить изменения.
    watermarker.save(r"D:\output.doc")
```

### См. также
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
