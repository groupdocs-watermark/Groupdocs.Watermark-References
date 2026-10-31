---
title: "Κλάση WatermarkerSettings"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Watermarker."
type: docs
url: /el/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Watermarker.

Ο τύπος WatermarkerSettings εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο του WatermarkerSettings. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Ο καταγραφέας που χρησιμοποιείται για την καταγραφή συμβάντων και σφαλμάτων κατά τη διαδικασία υδατογράφησης. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Τα αντικείμενα που μπορούν να αναζητηθούν και που θα συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. |

### Παράδειγμα

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
Οδηγοί εργασιών που χρησιμοποιούν `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
