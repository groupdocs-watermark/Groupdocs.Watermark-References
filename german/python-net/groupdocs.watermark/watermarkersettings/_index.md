---
title: "Klasse WatermarkerSettings"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Definiert Einstellungen zur Anpassung des Verhaltens des Watermarkers."
type: docs
url: /de/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Definiert Einstellungen zur Anpassung des Verhaltens des Watermarkers.

Der Typ WatermarkerSettings stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Initialisiert eine neue Instanz von WatermarkerSettings. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Der Logger, der zum Protokollieren von Ereignissen und Fehlern während der Wasserzeichenerstellung verwendet wird. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Die durchsuchbaren Objekte, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Ruft den Standardwert für die Klasse ab. |

### Beispiel

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
Aufgabenleitfäden, die `WatermarkerSettings` verwenden:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Siehe auch
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
