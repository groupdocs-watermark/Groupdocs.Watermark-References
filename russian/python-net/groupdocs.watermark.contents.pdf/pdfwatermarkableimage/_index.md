---
title: "Класс PdfWatermarkableImage"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет изображение внутри PDF‑документа."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
is_root: false
weight: 240
---


## PdfWatermarkableImage class

Представляет изображение внутри PDF‑документа.

Тип PdfWatermarkableImage раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/#image_data) | Инициализирует новый экземпляр класса [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) с использованием указанных данных изображения. |

### Методы
| Метод | Описание |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Добавляет водяной знак к этому [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Этот метод предполагает, что смещение и размер водяного знака измеряются в пикселях (если они заданы). (наследовано от [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (наследовано от [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Находит изображения в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Получает изображение в виде массива байтов. (наследовано от [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется по объектам, перечисленным в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Высота этого [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) в пикселях. (наследовано от [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Ширина этого WatermarkableImage в пикселях. (наследовано от [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Пример

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### См. также
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
