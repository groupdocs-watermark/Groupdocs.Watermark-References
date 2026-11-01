---
title: "Clase ColorRange"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un rango de colores usando la representación HSB del color RGB."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Representa un rango de colores usando la representación HSB del color RGB.

El tipo ColorRange expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Inicializa una nueva instancia de la clase [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/). |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Inicializa una nueva instancia de [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) con un color exacto especificado. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | La bandera que indica si solo el color vacío está dentro del rango. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | El valor final de brillo, que varía de 0.0 (negro) a 1.0 (blanco). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | El valor final de tono, en grados. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | El valor final de saturación. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | El valor inicial de brillo, que varía de 0.0 (negro) a 1.0 (blanco). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | El valor inicial de tono, en grados. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | El valor inicial de saturación. |

### Ejemplo

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Crear un rango de colores para la coincidencia del color de primer plano
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Guías de tareas que usan `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
