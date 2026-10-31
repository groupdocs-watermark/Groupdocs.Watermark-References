---
title: "Classe ColorRange"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente une gamme de couleurs utilisant la représentation HSB de la couleur RVB."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Représente une gamme de couleurs utilisant la représentation HSB de la couleur RVB.

Le type ColorRange expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Initialise une nouvelle instance de la classe [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/). |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Initialise une nouvelle instance de [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) avec une couleur exacte spécifiée. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Le drapeau indiquant si seule la couleur vide est dans la plage. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | La valeur finale de luminosité, allant de 0.0 (noir) à 1.0 (blanc). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | La valeur finale de teinte, en degrés. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | La valeur finale de saturation. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | La valeur de départ de luminosité, allant de 0.0 (noir) à 1.0 (blanc). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | La valeur de départ de teinte, en degrés. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | La valeur de départ de saturation. |

### Exemple

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Créer une plage de couleurs pour la correspondance de la couleur de premier plan
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Guides de tâches qui utilisent `ColorRange` :

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Voir aussi
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
