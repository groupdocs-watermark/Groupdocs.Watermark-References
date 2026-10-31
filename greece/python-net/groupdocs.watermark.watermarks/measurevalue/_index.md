---
title: "Κλάση MeasureValue"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια τιμή μέτρησης με συγκεκριμένο τύπο και αριθμητική τιμή."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Αντιπροσωπεύει μια τιμή μέτρησης με συγκεκριμένο τύπο και αριθμητική τιμή.

Ο τύπος MeasureValue εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Ο τύπος της μέτρησης. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Η αριθμητική τιμή της μέτρησης· πρέπει να είναι μεγαλύτερη από 0. |

### Παράδειγμα

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Δημιουργήστε μια μέτρηση που εκφράζεται ως ποσοστό της σελίδας
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
