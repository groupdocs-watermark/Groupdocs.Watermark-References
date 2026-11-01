---
title: "SearchableObjects klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Specificeert documentobjecten die moeten worden opgenomen in een watermerkzoekopdracht."
type: docs
url: /nl/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Specificeert documentobjecten die moeten worden opgenomen in een watermerkzoekopdracht.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Het SearchableObjects-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Initialiseert een nieuw exemplaar van de [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | De objecten in een Visio‑document die moeten worden opgenomen in een watermerkzoekopdracht. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | De objecten in een e‑mailbericht die moeten worden opgenomen in een watermerkzoekopdracht. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | De objecten in een PDF‑document die moeten worden opgenomen in een watermerkzoekopdracht. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | De objecten in een PowerPoint‑document die moeten worden opgenomen in een watermerkzoekopdracht. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | De objecten in een Excel‑document die moeten worden opgenomen in een watermerkzoekopdracht. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | De objecten in een Word‑document die moeten worden opgenomen in een watermerkzoekopdracht. |

### Voorbeeld

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
Taakgidsen die `SearchableObjects` gebruiken:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Zie ook
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
