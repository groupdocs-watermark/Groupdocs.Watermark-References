---
title: "Clase PdfAnnotationWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de anotación a un documento PDF."
type: docs
url: /es/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

Representa opciones de adición de marca de agua al agregar una marca de agua de anotación a un documento PDF.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

El tipo PdfAnnotationWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | El índice de página al que se añadirá la marca de agua. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | El valor que indica si la anotación se imprimirá pero no se mostrará en una aplicación de visualización de PDF. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1 aplica la marca de agua a todas las páginas (por defecto)
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### Ver también
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
