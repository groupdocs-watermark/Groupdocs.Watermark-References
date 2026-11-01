---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase ColorRange."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Crear un rango de color predeterminado
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Inicializa una nueva instancia de [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) con un color exacto especificado.

```python
def __init__(self, exact_color):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exact_color | `Color` | El color exacto del cual se crea el rango. |

### Ver también
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
