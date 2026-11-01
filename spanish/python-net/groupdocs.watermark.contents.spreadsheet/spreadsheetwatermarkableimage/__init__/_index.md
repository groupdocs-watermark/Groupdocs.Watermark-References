---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase SpreadsheetWatermarkableImage usando los datos de imagen especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inicializa una nueva instancia de la clase [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) usando los datos de imagen especificados.

```python
def __init__(self, image_data):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_data | `list[int]` | La matriz de bytes sin signo a partir de la cual crear el `SpreadsheetWatermarkableImage`. |

### Ejemplo

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Ver también
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
