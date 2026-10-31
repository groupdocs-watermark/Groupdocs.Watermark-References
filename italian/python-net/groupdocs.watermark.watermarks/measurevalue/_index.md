---
title: "Classe MeasureValue"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un valore di misura con un tipo specifico e valore numerico."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Rappresenta un valore di misura con un tipo specifico e valore numerico.

Il tipo MeasureValue espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Il tipo di misura. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Il valore numerico della misura; deve essere maggiore di 0. |

### Esempio

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Crea una misura espressa come percentuale della pagina
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Guide operative che utilizzano `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Vedi anche
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
