---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new instance of the SearchableObjects class."
type: docs
url: /python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) class.

```python
def __init__(self):
    ...
```

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search as gws

settings = gw.WatermarkerSettings()
settings.searchable_objects = gws.SearchableObjects(
    word_processing_searchable_objects=gws.WordProcessingSearchableObjects.HYPERLINKS
    | gws.WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=gws.SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=gws.PresentationSearchableObjects.SLIDES_BACKGROUNDS
    | gws.PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=gws.DiagramSearchableObjects.NONE,
    pdf_searchable_objects=gws.PdfSearchableObjects.ALL,
)
```

### See Also
* class [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)
