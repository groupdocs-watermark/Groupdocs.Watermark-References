---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο TextWatermark με το καθορισμένο κείμενο και τη γραμματοσειρά."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Αρχικοποιεί ένα νέο TextWatermark με το καθορισμένο κείμενο και τη γραμματοσειρά.

```python
def __init__(self, text, font):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα. |
| font | `Font` | Η γραμματοσειρά του κειμένου. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Δείτε επίσης
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
