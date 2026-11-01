---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PresentationWatermarkableImage usando los datos de imagen especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inicializa una nueva instancia de la clase [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) usando los datos de imagen especificados.

```python
def __init__(self, image_data):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_data | `list[int]` | La matriz de bytes sin signo a partir de la cual crear el `PresentationWatermarkableImage`. |

### Ejemplo

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Ver también
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
