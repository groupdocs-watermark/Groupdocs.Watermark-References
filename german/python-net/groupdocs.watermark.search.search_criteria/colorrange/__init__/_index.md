---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse ColorRange."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) Klasse.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Erstelle einen Standardfarbbereich
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Initialisiert eine neue Instanz von [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) mit einer angegebenen exakten Farbe.

```python
def __init__(self, exact_color):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exact_color | `Color` | Die genaue Farbe, aus der der Bereich erstellt wird. |

### Siehe auch
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
