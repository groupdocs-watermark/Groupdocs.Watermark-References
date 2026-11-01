---
title: "Класс SearchableObjects"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Указывает объекты документа, которые должны быть включены в поиск водяного знака."
type: docs
url: /ru/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Указывает объекты документа, которые должны быть включены в поиск водяного знака.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Тип SearchableObjects предоставляет следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Инициализирует новый экземпляр класса [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Объекты внутри документа Visio, которые должны быть включены в поиск водяных знаков. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Объекты внутри сообщения электронной почты, которые должны быть включены в поиск водяных знаков. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Объекты внутри PDF‑документа, которые должны быть включены в поиск водяных знаков. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Объекты внутри документа PowerPoint, которые должны быть включены в поиск водяных знаков. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Объекты внутри документа Excel, которые должны быть включены в поиск водяных знаков. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Объекты внутри документа Word, которые должны быть включены в поиск водяных знаков. |

### Пример

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
Руководства по задачам, использующие `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### См. также
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
