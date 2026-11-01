---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase WordProcessingLoadOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#password}

Inicializa una nueva instancia de la clase WordProcessingLoadOptions con una contraseña especificada.

```python
def __init__(self, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | `str` | La contraseña para abrir un contenido cifrado. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # realizar operaciones de marca de agua
    pass
```

### Ver también
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
