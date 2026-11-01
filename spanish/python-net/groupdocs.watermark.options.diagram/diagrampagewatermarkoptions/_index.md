---
title: "Clase DiagramPageWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de forma a una página específica de un documento Visio."
type: docs
url: /es/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

Representa opciones de adición de marca de agua al agregar una marca de agua de forma a una página específica de un documento Visio.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

El tipo DiagramPageWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | El índice de página al que se añadirá la marca de agua. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | La propiedad indica si la edición de la forma en Visio está prohibida. (heredada de [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.diagram import DiagramPageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./diagram.vsdx") as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42.0))

    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.vsdx")
```

### Ver también
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
