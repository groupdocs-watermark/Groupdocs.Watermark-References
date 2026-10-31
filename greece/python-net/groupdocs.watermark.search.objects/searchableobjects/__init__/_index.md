---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης SearchableObjects."
type: docs
url: /el/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def __init__(self):
    ...
```

### Παράδειγμα

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

### Δείτε επίσης
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
