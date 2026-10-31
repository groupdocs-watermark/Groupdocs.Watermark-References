---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بتهيئة نسخة جديدة من الفئة SearchableObjects."
type: docs
url: /ar/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثلاً جديداً من الفئة [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def __init__(self):
    ...
```

### مثال

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

### انظر أيضًا
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
