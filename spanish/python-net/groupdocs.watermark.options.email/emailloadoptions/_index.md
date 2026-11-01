---
title: "Clase EmailLoadOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones de carga del documento para un mensaje de correo electrónico."
type: docs
url: /es/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Representa las opciones de carga del documento para un mensaje de correo electrónico.

El tipo EmailLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | El tipo de archivo, indicando su formato (p. ej., docx, pdf, xlsx, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La familia de formato del documento, indicando su tipo (p. ej., Image, Pdf, Spreadsheet, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La contraseña para abrir un documento cifrado. (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # manipular contenido de correo electrónico aquí
    watermarker.save("./output.msg")
```

### Ver también
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
