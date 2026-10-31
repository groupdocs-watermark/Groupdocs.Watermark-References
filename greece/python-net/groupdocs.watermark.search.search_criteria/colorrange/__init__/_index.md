---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης ColorRange."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία της [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) κλάσης.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Δημιουργήστε ένα προεπιλεγμένο εύρος χρωμάτων
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Αρχικοποιεί μια νέα παρουσία της [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) με ένα καθορισμένο ακριβές χρώμα.

```python
def __init__(self, exact_color):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| exact_color | `Color` | Το ακριβές χρώμα από το οποίο δημιουργείται το εύρος. |

### Δείτε επίσης
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
