---
title: "Clase MeasureValue"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un valor de medida con un tipo específico y un valor numérico."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Representa un valor de medida con un tipo específico y un valor numérico.

El tipo MeasureValue expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | El tipo de medida. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | El valor numérico de la medida; debe ser mayor que 0. |

### Ejemplo

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Crear una medida expresada como porcentaje de la página
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Guías de tareas que utilizan `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ver también
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
