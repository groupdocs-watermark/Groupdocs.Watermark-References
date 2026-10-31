---
title: "ColorRange Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt einen Farbbereich dar, der die HSB-Darstellung der RGB-Farbe verwendet."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Stellt einen Farbbereich dar, der die HSB-Darstellung der RGB-Farbe verwendet.

Der Typ ColorRange stellt die folgenden Member bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Initialisiert eine neue Instanz der [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) Klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Initialisiert eine neue Instanz von [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) mit einer angegebenen exakten Farbe. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Das Flag, das angibt, ob nur die leere Farbe im Bereich liegt. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Der Endwert der Helligkeit, im Bereich von 0,0 (schwarz) bis 1,0 (weiß). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Der Endwert des Farbtons in Grad. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Der Endwert der Sättigung. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Der Startwert der Helligkeit, im Bereich von 0,0 (schwarz) bis 1,0 (weiß). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Der Startwert des Farbtons in Grad. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Der Startwert der Sättigung. |

### Beispiel

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Erstelle einen Farbbereich für die Übereinstimmung der Vordergrundfarbe
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Aufgabenleitfäden, die `ColorRange` verwenden:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Siehe auch
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
