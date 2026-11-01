---
title: "Clase WordProcessingLoadOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones de carga del documento para un documento Word."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Representa las opciones de carga del documento para un documento Word.

El tipo WordProcessingLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Inicializa una nueva instancia de la clase WordProcessingLoadOptions con una contraseña especificada. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | El tipo de archivo, indicando su formato (p. ej., docx, pdf, xlsx, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La familia de formato del documento, indicando su tipo (p. ej., Image, Pdf, Spreadsheet, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La contraseña para abrir un documento cifrado. (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # realizar operaciones sobre el contenido, p. ej., proteger, desproteger, agregar marcas de agua
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Ver también
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
