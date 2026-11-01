---
title: "SearchableObjects-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Specificerar dokumentobjekt som ska inkluderas i en vattenmärkesökning."
type: docs
url: /sv/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Specificerar dokumentobjekt som ska inkluderas i en vattenmärkesökning.

Läs mer:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Typen SearchableObjects exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Initierar en ny instans av klassen [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Objekten i ett Visio‑dokument som ska inkluderas i en vattenstämpelsökning. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Objekten i ett e‑postmeddelande som ska inkluderas i en vattenstämpelsökning. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Objekten i ett PDF‑dokument som ska inkluderas i en vattenstämpelsökning. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Objekten i ett PowerPoint‑dokument som ska inkluderas i en vattenstämpelsökning. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Objekten i ett Excel‑dokument som ska inkluderas i en vattenstämpelsökning. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Objekten i ett Word‑dokument som ska inkluderas i en vattenstämpelsökning. |

### Exempel

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
Uppgiftsguider som använder `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Se även
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
