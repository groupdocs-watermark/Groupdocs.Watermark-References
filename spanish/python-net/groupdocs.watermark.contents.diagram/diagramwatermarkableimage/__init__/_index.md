---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase DiagramWatermarkableImage usando los datos de imagen especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inicializa una nueva instancia de la clase [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) usando los datos de imagen especificados.

```python
def __init__(self, image_data):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_data | `list[int]` | La matriz de bytes sin signo a partir de la cual crear el `DiagramWatermarkableImage`. |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Ver también
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
