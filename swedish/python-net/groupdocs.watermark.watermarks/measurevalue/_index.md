---
title: "MeasureValue-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar ett mätningsvärde med en specifik typ och numeriskt värde."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Representerar ett mätningsvärde med en specifik typ och numeriskt värde.

MeasureValue‑typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Mätningens typ. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Det numeriska värdet för mätningen; det måste vara större än 0. |

### Exempel

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Skapa en mätning uttryckt som en procentandel av sidan
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Uppgiftsguider som använder `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Se även
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
