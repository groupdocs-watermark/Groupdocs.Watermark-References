---
title: "Clase PresentationWatermarkableImage"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una imagen dentro de un documento de PowerPoint."
type: docs
url: /es/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
is_root: false
weight: 250
---


## PresentationWatermarkableImage class

Representa una imagen dentro de un documento de PowerPoint.

El tipo PresentationWatermarkableImage expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/#image_data) | Inicializa una nueva instancia de la clase [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) usando los datos de imagen especificados. |

### Métodos
| Método | Descripción |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Añade una marca de agua a este [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Este método asume que el desplazamiento y el tamaño de la marca de agua se miden en píxeles (si se asignan). (heredado de [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (heredado de [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Obtiene la imagen como una matriz de bytes. (heredado de [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | La altura de este [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) en píxeles. (heredado de [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | El ancho de este WatermarkableImage en píxeles. (heredado de [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("image.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Ver también
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
