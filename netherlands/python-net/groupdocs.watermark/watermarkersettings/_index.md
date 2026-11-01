---
title: "WatermarkerSettings klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Definieert instellingen voor het aanpassen van het gedrag van Watermarker."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Definieert instellingen voor het aanpassen van het gedrag van Watermarker.

Het type WatermarkerSettings bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Initialiseert een nieuw exemplaar van WatermarkerSettings. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | De logger die wordt gebruikt voor het loggen van gebeurtenissen en fouten tijdens het watermerken. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | De doorzoekbare objecten die moeten worden opgenomen in een watermerkzoekopdracht. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Haalt de standaardwaarde op voor de klasse. |

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
Taakgidsen die `WatermarkerSettings` gebruiken:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Zie ook
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
