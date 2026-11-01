---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PresentationLoadOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

def remove_slide_background():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.slides[0].image_fill_format.background_image = None
        watermarker.save("./output.pptx")
```

## __init__ {#password}

Inicializa una nueva instancia de la clase PresentationLoadOptions con una contraseña especificada.

```python
def __init__(self, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | `str` | La contraseña para abrir un contenido cifrado. |

### Ejemplo

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### Ver también
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
