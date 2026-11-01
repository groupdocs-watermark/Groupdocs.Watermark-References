---
title: "Clase SearchableObjects"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Especifica los objetos del documento que se incluirán en una búsqueda de marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Especifica los objetos del documento que se incluirán en una búsqueda de marca de agua.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

El tipo SearchableObjects expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Inicializa una nueva instancia de la clase [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Los objetos dentro de un documento Visio que se incluirán en una búsqueda de marcas de agua. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Los objetos dentro de un mensaje de correo electrónico que se incluirán en una búsqueda de marcas de agua. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Los objetos dentro de un documento PDF que se incluirán en una búsqueda de marcas de agua. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Los objetos dentro de un documento PowerPoint que se incluirán en una búsqueda de marcas de agua. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Los objetos dentro de un documento Excel que se incluirán en una búsqueda de marcas de agua. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Los objetos dentro de un documento Word que se incluirán en una búsqueda de marcas de agua. |

### Ejemplo

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
Guías de tareas que usan `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ver también
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
