---
title: "SearchableObjects classe"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Spécifie les objets de document qui doivent être inclus dans une recherche de filigrane."
type: docs
url: /fr/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Spécifie les objets de document qui doivent être inclus dans une recherche de filigrane.

En savoir plus :
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Le type SearchableObjects expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Initialise une nouvelle instance de la classe [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Les objets à l'intérieur d'un document Visio qui doivent être inclus dans une recherche de filigrane. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Les objets à l'intérieur d'un message électronique qui doivent être inclus dans une recherche de filigrane. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Les objets à l'intérieur d'un document PDF qui doivent être inclus dans une recherche de filigrane. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Les objets à l'intérieur d'un document PowerPoint qui doivent être inclus dans une recherche de filigrane. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Les objets à l'intérieur d'un document Excel qui doivent être inclus dans une recherche de filigrane. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Les objets à l'intérieur d'un document Word qui doivent être inclus dans une recherche de filigrane. |

### Exemple

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
Guides de tâches qui utilisent `SearchableObjects` :

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Voir aussi
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
