---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe SearchableObjects."
type: docs
url: /it/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def __init__(self):
    ...
```

### Esempio

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

### Vedi anche
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
