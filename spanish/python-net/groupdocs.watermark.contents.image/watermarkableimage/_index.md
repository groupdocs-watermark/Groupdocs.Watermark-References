---
title: "Clase WatermarkableImage"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una imagen dentro de un documento."
type: docs
url: /es/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Representa una imagen dentro de un documento.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

El tipo WatermarkableImage expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Añade una marca de agua a este [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Este método asume que el desplazamiento y el tamaño de la marca de agua se miden en píxeles (si se asignan). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Obtiene la imagen como una matriz de bytes. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | La altura de este [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) en píxeles. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | El ancho de este WatermarkableImage en píxeles. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Inicializar marca de agua de texto.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Encontrar todas las imágenes en el documento.
    images = watermarker.get_images()

    # Agregar marca de agua a cada imagen.
    for img in images:
        img.add(watermark)

    # Guardar cambios.
    watermarker.save(r"D:\output.doc")
```

### Ver también
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
