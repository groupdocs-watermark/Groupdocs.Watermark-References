---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av ColorRange-klassen."
type: docs
url: /sv/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) klassen.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Skapa ett standardfärgområde
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Initierar en ny instans av [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) med en specificerad exakt färg.

```python
def __init__(self, exact_color):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exact_color | `Color` | Den exakta färgen som området skapas från. |

### Se även
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
