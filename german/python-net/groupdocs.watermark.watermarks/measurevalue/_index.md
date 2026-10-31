---
title: "MeasureValue-Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt einen Messwert mit einem bestimmten Typ und numerischen Wert dar."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Stellt einen Messwert mit einem bestimmten Typ und numerischen Wert dar.

Der MeasureValue-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Der Typ der Messung. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Der numerische Wert der Messung; er muss größer als 0 sein. |

### Beispiel

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Erstelle eine Messung, ausgedrückt als Prozentsatz der Seite
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Aufgabenleitfäden, die `MeasureValue` verwenden:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Siehe auch
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
