---
title: "MeasureValue klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een meetwaarde voor met een specifiek type en numerieke waarde."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Stelt een meetwaarde voor met een specifiek type en numerieke waarde.

Het MeasureValue-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Het type meting. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | De numerieke waarde van de meting; deze moet groter zijn dan 0. |

### Voorbeeld

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Maak een meting uitgedrukt als een percentage van de pagina
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Taakgidsen die `MeasureValue` gebruiken:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Zie ook
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
