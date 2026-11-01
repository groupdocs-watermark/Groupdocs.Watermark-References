---
title: "Clase TiffImageWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen TIFF."
type: docs
url: /es/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
is_root: false
weight: 100
---


## TiffImageWatermarkOptions class

Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen TIFF.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

El tipo TiffImageWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/#frame_index) | Inicializa una nueva instancia de [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) con un índice de fotograma especificado. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | El índice del fotograma al que se añadirá una marca de agua. (heredado de [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

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
