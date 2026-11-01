---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de ColorRange-klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Maak een standaard kleurenbereik
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Initialiseert een nieuw exemplaar van [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) met een opgegeven exacte kleur.

```python
def __init__(self, exact_color):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| exact_color | `Color` | De exacte kleur waaruit het bereik wordt gemaakt. |

### Zie ook
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
