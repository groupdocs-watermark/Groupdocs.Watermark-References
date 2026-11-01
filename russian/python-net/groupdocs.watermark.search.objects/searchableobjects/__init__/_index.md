---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса SearchableObjects."
type: docs
url: /ru/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.watermark import WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects,
    WordProcessingSearchableObjects,
    PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)
```

### См. также
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
