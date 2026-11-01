---
title: "Clase TiffImageLoadOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de carga de imagen para una imagen TIFF."
type: docs
url: /es/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/
is_root: false
weight: 80
---


## TiffImageLoadOptions class

Representa opciones de carga de imagen para una imagen TIFF.

El tipo TiffImageLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/__init__/) | Inicializa una nueva instancia de la clase TiffImageLoadOptions. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | El tipo de archivo, indicando su formato (p. ej., docx, pdf, xlsx, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La familia de formato del documento, indicando su tipo (p. ej., Image, Pdf, Spreadsheet, etc.). (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | La contraseña para abrir un documento cifrado. (heredado de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.red
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER

    options = TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)

    watermarker.save("./output.tiff")
```

### Ver también
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
