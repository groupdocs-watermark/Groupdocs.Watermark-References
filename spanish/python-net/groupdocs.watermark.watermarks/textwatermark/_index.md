---
title: "Clase TextWatermark"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una marca de agua de texto."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Representa una marca de agua de texto.

Aprende más:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

El tipo TextWatermark expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Inicializa un nuevo TextWatermark con el texto y la fuente especificados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | El color de fondo del texto. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | La fuente del texto. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | El color de primer plano del texto. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | La configuración de relleno de este TextWatermark, aplicable solo a archivos de imagen. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | El texto que se usará como marca de agua. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | La alineación del texto de la marca de agua. |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | La propiedad que indica si el tamaño y las coordenadas de la marca de agua se calculan considerando los márgenes del contenedor. Si se establece en True, los cálculos consideran los márgenes del contenedor; por defecto el valor es False y los márgenes del contenedor se ignoran. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | La altura deseada de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | La alineación horizontal de esta Watermark. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | La propiedad que indica si la marca de agua debe colocarse en el fondo. Si es true, la marca de agua se coloca en la parte inferior; de lo contrario, se coloca en la parte superior (por defecto es False). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | La configuración de márgenes de esta Watermark. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | La opacidad de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | La configuración de configuración de páginas de este Watermark. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | El ángulo de rotación de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) en grados. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | La propiedad indica si guardar información sobre marcas de agua añadidas en los metadatos del documento. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | El factor de escala de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), que define cómo el tamaño de la marca de agua depende del tamaño del elemento padre. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | El tipo de dimensionado de la marca de agua. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Las opciones para definir una marca de agua repetida. (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | La alineación vertical de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | El ancho deseado de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | La coordenada x de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | La coordenada y de este [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (heredado de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

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

### Guides
Guías de tareas que usan `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ver también
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
