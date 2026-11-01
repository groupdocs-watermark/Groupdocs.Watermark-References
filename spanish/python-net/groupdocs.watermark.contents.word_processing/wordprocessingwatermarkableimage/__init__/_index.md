---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase WordProcessingWatermarkableImage usando los datos de imagen especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inicializa una nueva instancia de la clase [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) usando los datos de imagen especificados.

```python
def __init__(self, image_data):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_data | `list[int]` | La matriz de bytes sin signo a partir de la cual crear el `WordProcessingWatermarkableImage`. |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Ver también
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
