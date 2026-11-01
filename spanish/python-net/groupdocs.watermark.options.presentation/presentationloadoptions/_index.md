---
title: "Clase PresentationLoadOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones de carga de documento para un documento Presentation."
type: docs
url: /es/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Representa las opciones de carga de documento para un documento Presentation.

El tipo PresentationLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Inicializa una nueva instancia de la clase PresentationLoadOptions con una contraseña especificada. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | El tipo de archivo, indicando su formato (p. ej., docx, pdf, xlsx, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La familia de formato del documento, indicando su tipo (p. ej., Image, Pdf, Spreadsheet, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La contraseña para abrir un documento cifrado. (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # trabajar con el documento
    pass
```

### Ver también
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
