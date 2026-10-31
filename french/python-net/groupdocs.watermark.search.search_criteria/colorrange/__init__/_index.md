---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe ColorRange."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/).

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Créer une plage de couleurs par défaut
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Initialise une nouvelle instance de [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) avec une couleur exacte spécifiée.

```python
def __init__(self, exact_color):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| exact_color | `Color` | La couleur exacte à partir de laquelle la plage est créée. |

### Voir aussi
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
