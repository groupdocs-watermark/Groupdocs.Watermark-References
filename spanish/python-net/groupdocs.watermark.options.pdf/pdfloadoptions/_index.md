---
title: "Clase PdfLoadOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de carga de documento para un documento PDF."
type: docs
url: /es/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/
is_root: false
weight: 30
---


## PdfLoadOptions class

Representa opciones de carga de documento para un documento PDF.

El tipo PdfLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/#password) | Inicializa una nueva instancia de la clase [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) con una contraseña especificada. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | El tipo de archivo, indicando su formato (p. ej., docx, pdf, xlsx, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La familia de formato del documento, indicando su tipo (p. ej., Image, Pdf, Spreadsheet, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La contraseña para abrir un documento cifrado. (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    # realiza operaciones en el watermarker
    pass
```

### Ver también
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
