---
title: "Clase MultiframeImageWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen multi-cuadro."
type: docs
url: /es/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

Representa opciones de adición de marca de agua al agregar una marca de agua a una imagen multi-cuadro.

Más información: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

El tipo MultiframeImageWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | Inicializa una nueva instancia de la clase [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) con un índice especificado del fotograma. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | El índice del fotograma al que se añadirá una marca de agua. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Ver también
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
