---
title: "Clase PreviewOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas."
type: docs
url: /es/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Proporciona opciones para establecer requisitos y delegados de flujo para la generación de vistas previas.

El tipo PreviewOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Inicializa una nueva instancia de PreviewOptions que cierra el flujo de salida después de su uso. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Inicializa una nueva instancia de PreviewOptions que devuelve el flujo de salida al cliente para su uso posterior. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | El delegado de creación del flujo de página usado para obtener un flujo de escritura para cada página renderizada. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | La altura de la vista previa de la página. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | La matriz de números de página para generar vistas previas. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | El formato de imagen de la vista previa. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | El delegado de finalización de la vista previa de la página. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | El ancho de la vista previa de la página. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Proporcione un flujo de archivo escribible para cada página a renderizar
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
Guías de tareas que usan `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### Ver también
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
