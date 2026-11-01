---
title: "Clase TileOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones para configurar marcas de agua en modo mosaico."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/tileoptions/
is_root: false
weight: 140
---


## TileOptions class

Representa opciones para configurar marcas de agua en modo mosaico.

El tipo TileOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/__init__/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [line_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/line_spacing/) | El espaciado entre líneas para marcas de agua en modo mosaico. |
| [rotate_around_origin](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/rotate_around_origin/) | La propiedad indica si las marcas de agua repetidas se rotan alrededor del centro del documento. |
| [tile_type](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/tile_type/) | El tipo de alineación de mosaico para marcas de agua. |
| [watermark_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/watermark_spacing/) | El espaciado entre series para marcas de agua en modo mosaico. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.gray
    watermark.opacity = 0.3
    watermark.rotate_angle = -45.0
    watermark.text_alignment = TextAlignment.CENTER

    line_spacing = MeasureValue()
    line_spacing.measure_type = TileMeasureType.PERCENT
    line_spacing.value = 12.0

    watermark_spacing = MeasureValue()
    watermark_spacing.measure_type = TileMeasureType.PERCENT
    watermark_spacing.value = 10.0

    tile_options = TileOptions()
    tile_options.tile_type = TileType.ONE_THIRD_OFFSET
    tile_options.line_spacing = line_spacing
    tile_options.watermark_spacing = watermark_spacing
    watermark.tile_options = tile_options

    watermarker.add(watermark)
```

### Guides
Guías de tareas que utilizan `TileOptions`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ver también
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
