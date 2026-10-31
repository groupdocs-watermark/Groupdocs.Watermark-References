---
title: "classe WatermarkerSettings"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Definisce le impostazioni per personalizzare il comportamento di Watermarker."
type: docs
url: /it/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Definisce le impostazioni per personalizzare il comportamento di Watermarker.

Il tipo WatermarkerSettings espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Inizializza una nuova istanza di WatermarkerSettings. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Il logger utilizzato per registrare eventi ed errori durante il watermarking. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Gli oggetti ricercabili da includere in una ricerca di watermark. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Ottiene il valore predefinito per la classe. |

### Esempio

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
Guide operative che utilizzano `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Vedi anche
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
