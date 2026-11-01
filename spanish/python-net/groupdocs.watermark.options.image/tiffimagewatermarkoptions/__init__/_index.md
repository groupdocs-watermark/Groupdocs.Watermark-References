---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase TiffImageWatermarkOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

def add_watermark_to_image():
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

## __init__ {#frame_index}

Inicializa una nueva instancia de [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) con un índice de fotograma especificado.

```python
def __init__(self, frame_index):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| frame_index | `int` | El índice del fotograma para añadir la marca de agua. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

def add_watermark_to_image():
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
* class [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/)
