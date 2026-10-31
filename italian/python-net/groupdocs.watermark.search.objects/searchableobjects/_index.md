---
title: "Classe SearchableObjects"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Specifica gli oggetti del documento da includere in una ricerca di filigrana."
type: docs
url: /it/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Specifica gli oggetti del documento da includere in una ricerca di filigrana.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Il tipo SearchableObjects espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Inizializza una nuova istanza della classe [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Gli oggetti all'interno di un documento Visio che devono essere inclusi nella ricerca di filigrana. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Gli oggetti all'interno di un messaggio email che devono essere inclusi nella ricerca di filigrana. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Gli oggetti all'interno di un documento PDF che devono essere inclusi nella ricerca di filigrana. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Gli oggetti all'interno di un documento PowerPoint che devono essere inclusi nella ricerca di filigrana. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Gli oggetti all'interno di un documento Excel che devono essere inclusi nella ricerca di filigrana. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Gli oggetti all'interno di un documento Word che devono essere inclusi nella ricerca di filigrana. |

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
Guide operative che utilizzano `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Vedi anche
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
