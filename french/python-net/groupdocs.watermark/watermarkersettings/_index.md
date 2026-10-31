---
title: "Classe WatermarkerSettings"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Définit les paramètres pour personnaliser le comportement du Watermarker."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Définit les paramètres pour personnaliser le comportement du Watermarker.

Le type WatermarkerSettings expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Initialise une nouvelle instance de WatermarkerSettings. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Le logger utilisé pour consigner les événements et les erreurs pendant le filigrannage. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Les objets recherchables qui doivent être inclus dans une recherche de filigrane. |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Obtient la valeur par défaut pour la classe. |

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
Guides de tâches qui utilisent `WatermarkerSettings` :

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Voir aussi
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
