---
title: "add μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο.

Μάθετε περισσότερα για την προσθήκη υδατοσημάτων στην τεκμηρίωση του GroupDocs.

```python
def add(self, watermark):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| watermark | `Watermark` | Το υδατοσήμα για προσθήκη στο έγγραφο. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

Προσθέτει ένα υδατογράφημα στο φορτωμένο έγγραφο χρησιμοποιώντας επιλογές υδατογραφήματος.

Μάθετε περισσότερα για την προσθήκη υδατοσημάτων: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| watermark | `Watermark` | Το υδατοσήμα για προσθήκη στο έγγραφο. |
| options | `WatermarkOptions` | Πρόσθετες επιλογές για χρήση κατά την προσθήκη του υδατοσημείου. |

**Returns:** None.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
