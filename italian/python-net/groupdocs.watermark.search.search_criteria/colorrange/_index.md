---
title: "Classe ColorRange"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta una gamma di colori usando la rappresentazione HSB del colore RGB."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Rappresenta una gamma di colori usando la rappresentazione HSB del colore RGB.

Il tipo ColorRange espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Inizializza una nuova istanza della classe [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/). |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Inizializza una nuova istanza di [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) con un colore esatto specificato. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Il flag che indica se solo il colore vuoto è nell'intervallo. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Il valore finale di luminosità, compreso tra 0,0 (nero) e 1,0 (bianco). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Il valore finale di tonalità, in gradi. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Il valore finale di saturazione. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Il valore iniziale di luminosità, compreso tra 0,0 (nero) e 1,0 (bianco). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Il valore iniziale di tonalità, in gradi. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Il valore iniziale di saturazione. |

### Esempio

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Crea un intervallo di colore per il confronto del colore di primo piano
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Guide operative che utilizzano `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Vedi anche
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
