---
title: "Clase WatermarkerSettings"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Define configuraciones para personalizar el comportamiento de Watermarker."
type: docs
url: /es/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Define configuraciones para personalizar el comportamiento de Watermarker.

El tipo WatermarkerSettings expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Inicializa una nueva instancia de WatermarkerSettings. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | El logger usado para registrar eventos y errores durante la aplicación de marcas de agua. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Los objetos buscables que se incluirán en una búsqueda de marca de agua. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Obtiene el valor predeterminado para la clase. |

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
Guías de tareas que usan `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ver también
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
