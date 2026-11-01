---
title: "Clase PdfArtifactWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de artefacto a un documento PDF."
type: docs
url: /es/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

Representa opciones de adición de marca de agua al agregar una marca de agua de artefacto a un documento PDF.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

El tipo PdfArtifactWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | El índice de página al que se añadirá la marca de agua. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfArtifactWatermarkOptions

with Watermarker("./test.pdf", PdfLoadOptions()) as watermarker:
    with ImageWatermark("./icon.png") as watermark:
        watermark.horizontal_alignment = HorizontalAlignment.RIGHT
        watermark.vertical_alignment = VerticalAlignment.BOTTOM
        options = PdfArtifactWatermarkOptions()
        options.page_index = -1  # default: all pages
        watermarker.add(watermark, options)
        watermarker.save()
```

### Ver también
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
