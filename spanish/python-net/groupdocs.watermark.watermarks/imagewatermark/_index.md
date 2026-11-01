---
title: "Clase ImageWatermark"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una marca de agua de imagen."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Representa una marca de agua de imagen.

Aprende más:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

El tipo ImageWatermark expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Inicializa una nueva instancia de ImageWatermark con una ruta de archivo especificada. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Inicializa un nuevo ImageWatermark con el flujo de imagen proporcionado. |

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Libera la instancia actual. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
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
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Cargar datos de imagen en un flujo
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Abrir el documento y añadir la marca de agua de imagen
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Guías de tareas que usan `ImageWatermark`:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Ver también
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
