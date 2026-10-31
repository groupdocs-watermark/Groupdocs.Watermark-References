---
title: "Κλάση SearchableObjects"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Καθορίζει αντικείμενα εγγράφου που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος."
type: docs
url: /el/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Καθορίζει αντικείμενα εγγράφου που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Ο τύπος SearchableObjects εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Τα αντικείμενα μέσα σε ένα έγγραφο Visio που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Τα αντικείμενα μέσα σε ένα μήνυμα email που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Τα αντικείμενα μέσα σε ένα έγγραφο PDF που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Τα αντικείμενα μέσα σε ένα έγγραφο PowerPoint που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Τα αντικείμενα μέσα σε ένα έγγραφο Excel που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Τα αντικείμενα μέσα σε ένα έγγραφο Word που πρέπει να συμπεριληφθούν σε αναζήτηση υδατογραφήματος. |

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
Οδηγοί εργασιών που χρησιμοποιούν `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
