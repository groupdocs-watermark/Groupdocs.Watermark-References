---
title: "Klassen WatermarkerSettings"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Definierar inställningar för att anpassa Watermarker-beteende."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Definierar inställningar för att anpassa Watermarker-beteende.

Typen WatermarkerSettings visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Initierar en ny instans av WatermarkerSettings. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Loggaren som används för att logga händelser och fel under vattenmärkning. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | De sökbara objekten som ska inkluderas i en vattenmärkesökning. |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Hämtar standardvärdet för klassen. |

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
Uppgiftsguider som använder `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Se även
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
