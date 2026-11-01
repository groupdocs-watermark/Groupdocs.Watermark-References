---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa un nuevo TextWatermark con el texto y la fuente especificados."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Inicializa un nuevo TextWatermark con el texto y la fuente especificados.

```python
def __init__(self, text, font):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | El texto que se usará como marca de agua. |
| font | `Font` | La fuente del texto. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Ver también
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
