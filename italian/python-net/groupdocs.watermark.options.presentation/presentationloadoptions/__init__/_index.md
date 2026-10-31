---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe PresentationLoadOptions."
type: docs
url: /it/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/).

```python
def __init__(self):
    ...
```

### Esempio

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

Inizializza una nuova istanza della classe PresentationLoadOptions con una password specificata.

```python
def __init__(self, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | `str` | La password per aprire un contenuto crittografato. |

### Esempio

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### Vedi anche
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
