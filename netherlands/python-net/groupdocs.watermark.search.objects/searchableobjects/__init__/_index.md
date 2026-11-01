---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de SearchableObjects-klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

### Zie ook
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
