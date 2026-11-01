---
title: "add método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Añade una marca de agua al documento cargado."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Añade una marca de agua al documento cargado.

Aprenda más sobre la incorporación de marcas de agua en la documentación de GroupDocs.

```python
def add(self, watermark):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| watermark | `Watermark` | La marca de agua a agregar al documento. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

Añade una marca de agua al documento cargado usando opciones de marca de agua.

Obtenga más información sobre la incorporación de marcas de agua: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| watermark | `Watermark` | La marca de agua a agregar al documento. |
| options | `WatermarkOptions` | Opciones adicionales para usar al agregar la marca de agua. |

**Returns:** None.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
