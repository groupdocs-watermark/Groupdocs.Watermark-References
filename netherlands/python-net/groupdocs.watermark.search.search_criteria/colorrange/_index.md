---
title: "ColorRange klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een bereik van kleuren voor met behulp van HSB-representatie van RGB-kleur."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Stelt een bereik van kleuren voor met behulp van HSB-representatie van RGB-kleur.

Het type ColorRange exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Initialiseert een nieuw exemplaar van de [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Initialiseert een nieuw exemplaar van [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) met een opgegeven exacte kleur. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | De vlag die aangeeft of alleen de lege kleur binnen het bereik ligt. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | De eindwaarde van de helderheid, variërend van 0,0 (zwart) tot 1,0 (wit). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | De eindwaarde van de tint, in graden. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | De eindwaarde van de verzadiging. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | De startwaarde van de helderheid, variërend van 0,0 (zwart) tot 1,0 (wit). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | De startwaarde van de tint, in graden. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | De startwaarde van de verzadiging. |

### Voorbeeld

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Maak een kleurenbereik voor het matchen van voorgrondkleur
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Taakgidsen die `ColorRange` gebruiken:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Zie ook
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
