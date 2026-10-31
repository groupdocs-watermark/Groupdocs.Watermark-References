---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe **ColorRange**."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/).

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Crea un intervallo di colore predefinito
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Inizializza una nuova istanza di [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) con un colore esatto specificato.

```python
def __init__(self, exact_color):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| exact_color | `Color` | Il colore esatto da cui viene creato l'intervallo. |

### Vedi anche
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
