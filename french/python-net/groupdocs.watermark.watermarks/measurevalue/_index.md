---
title: "Classe MeasureValue"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente une valeur de mesure avec un type spécifique et une valeur numérique."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Représente une valeur de mesure avec un type spécifique et une valeur numérique.

Le type MeasureValue expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Le type de mesure. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | La valeur numérique de la mesure ; elle doit être supérieure à 0. |

### Exemple

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Créer une mesure exprimée en pourcentage de la page
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Guides de tâches qui utilisent `MeasureValue` :

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Voir aussi
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
