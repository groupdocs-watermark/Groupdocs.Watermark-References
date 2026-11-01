---
title: "Clase ImageInpaintingPossibleWatermark"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una región de imagen especificada manualmente que debe ser repintada (rellenada usando los píxeles circundantes)."
type: docs
url: /es/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
is_root: false
weight: 110
---


## ImageInpaintingPossibleWatermark class

Representa una región de imagen especificada manualmente que debe ser repintada (rellenada usando los píxeles circundantes).

El tipo ImageInpaintingPossibleWatermark expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/__init__/) | Inicializa una nueva instancia de ImageInpaintingPossibleWatermark. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [method](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method/) | El algoritmo de inpainting utilizado para la detección de marcas de agua posibles. El valor predeterminado es `InpaintingMethod.patch_based`. |
| [parent](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent/) | El padre de este ImageInpaintingPossibleWatermark. Siempre devuelve None porque la región se especifica manualmente. |
| [patch_size](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patch_size/) | El tamaño del parche utilizado por el algoritmo (impar, 5-11). |
| [polygons](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons/) | Las regiones poligonales que se van a repintar, expresadas como una lista de polígonos donde cada polígono es una lista de vértices en píxeles de la imagen. |
| [rectangles](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles/) | Las áreas rectangulares que se van a repintar, en píxeles de la imagen. |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | La colección de fragmentos de texto formateado de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [height](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/height/) | La altura de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | La imagen de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) o None si la marca de agua no tiene imagen. (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | El número de página donde se coloca la marca de agua. (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/rotate_angle/) | El ángulo de rotación de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) en grados. (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [text](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/text/) | El texto de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/unit_of_measurement/) | La unidad de medida de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [width](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/width/) | El ancho de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [x](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/x/) | La coordenada x de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [y](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/y/) | La coordenada y de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Ver también
* module [`groupdocs.watermark.search.watermarks`](/watermark/python-net/groupdocs.watermark.search.watermarks/)
