---
title: "SearchableObjects Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Gibt Dokumentobjekte an, die in eine Wasserzeichen-Suche einbezogen werden sollen."
type: docs
url: /de/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Gibt Dokumentobjekte an, die in eine Wasserzeichen-Suche einbezogen werden sollen.

Mehr erfahren:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Der Typ SearchableObjects stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Initialisiert eine neue Instanz der [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Die Objekte in einem Visio-Dokument, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Die Objekte in einer E‑Mail‑Nachricht, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Die Objekte in einem PDF-Dokument, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Die Objekte in einem PowerPoint-Dokument, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Die Objekte in einem Excel-Dokument, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Die Objekte in einem Word-Dokument, die in einer Wasserzeichen‑Suche einbezogen werden sollen. |

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
Aufgabenleitfäden, die `SearchableObjects` verwenden:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Siehe auch
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
