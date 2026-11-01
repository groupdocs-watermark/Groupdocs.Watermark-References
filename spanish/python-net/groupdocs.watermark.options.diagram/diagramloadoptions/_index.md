---
title: "Clase DiagramLoadOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de carga de documento para un documento Visio."
type: docs
url: /es/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Representa opciones de carga de documento para un documento Visio.

El tipo DiagramLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | Inicializa una nueva instancia de la clase [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) con una contraseña especificada. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | El tipo de archivo, indicando su formato (p. ej., docx, pdf, xlsx, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La familia de formato del documento, indicando su tipo (p. ej., Image, Pdf, Spreadsheet, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La contraseña para abrir un documento cifrado. (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    # manipula formas aquí
    watermarker.save("output.vsdx")
```

### Ver también
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
