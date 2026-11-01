---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PdfWatermarkableImage usando los datos de imagen especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inicializa una nueva instancia de la clase [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) usando los datos de imagen especificados.

```python
def __init__(self, image_data):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_data | `list[int]` | La matriz de bytes sin signo a partir de la cual crear el `PdfWatermarkableImage`. |

### Ejemplo

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Ver también
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
