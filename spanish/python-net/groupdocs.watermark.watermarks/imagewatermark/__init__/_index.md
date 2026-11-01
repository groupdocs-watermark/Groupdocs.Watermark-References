---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de ImageWatermark con una ruta de archivo especificada."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Inicializa una nueva instancia de ImageWatermark con una ruta de archivo especificada.

```python
def __init__(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta a la imagen que se utilizará como marca de agua. |

### Ejemplo

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Inicializa un nuevo ImageWatermark con el flujo de imagen proporcionado.

```python
def __init__(self, stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo que contiene la imagen que se utilizará como marca de agua. |

### Ejemplo

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### Ver también
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
