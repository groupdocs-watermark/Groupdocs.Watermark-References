---
title: "Clase DiagramShapeWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de forma a un documento Visio."
type: docs
url: /es/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
is_root: false
weight: 50
---


## DiagramShapeWatermarkOptions class

Representa opciones de adición de marca de agua al agregar una marca de agua de forma a un documento Visio.

- Add watermarks to diagram documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

El tipo DiagramShapeWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`DiagramShapeWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [placement_type](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placement_type/) | El valor que especifica a qué páginas se debe agregar una marca de agua. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | La propiedad indica si la edición de la forma en Visio está prohibida. (heredada de [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.diagram import DiagramShapeWatermarkOptions
from groupdocs.watermark.contents.diagram import DiagramWatermarkPlacementType

def add_watermark_to_diagram():
    with Watermarker("./diagram.vsdx") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = DiagramShapeWatermarkOptions()
        options.placement_type = DiagramWatermarkPlacementType.BACKGROUND_PAGES
        watermarker.add(watermark, options)

        watermarker.save("./output.vsdx")
```

### Ver también
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
