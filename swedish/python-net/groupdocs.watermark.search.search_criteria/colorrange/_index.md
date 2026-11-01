---
title: "ColorRange-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar ett färgomfång som använder HSB-representation av RGB-färg."
type: docs
url: /sv/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Representerar ett färgomfång som använder HSB-representation av RGB-färg.

ColorRange-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Initierar en ny instans av [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) klassen. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Initierar en ny instans av [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) med en specificerad exakt färg. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Flaggan som indikerar om endast den tomma färgen är inom intervallet. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Det avslutande ljusstyrkevärdet, i intervallet 0.0 (svart) till 1.0 (vitt). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Det avslutande nyansvärdet, i grader. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Det avslutande mättnadsvärdet. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Det startande ljusstyrkevärdet, i intervallet 0.0 (svart) till 1.0 (vitt). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Det startande nyansvärdet, i grader. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Det startande mättnadsvärdet. |

### Exempel

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Skapa ett färgintervall för matchning av förgrundsfärg
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Uppgiftsguider som använder `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Se även
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
