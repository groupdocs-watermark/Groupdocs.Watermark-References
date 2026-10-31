---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse SearchableObjects."
type: docs
url: /de/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) Klasse.

```python
def __init__(self):
    ...
```

### Beispiel

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

### Siehe auch
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
