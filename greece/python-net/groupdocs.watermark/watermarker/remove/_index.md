---
title: "remove μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αφαιρεί ένα υδατογράφημα από το έγγραφο."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Αφαιρεί ένα υδατογράφημα από το έγγραφο.

Μάθετε περισσότερα για την αφαίρεση υδατογραφιών: Αφαίρεση των εντοπισμένων υδατογραφιών.

```python
def remove(self, possible_watermark):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Η υδατογραφία προς αφαίρεση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Αφαιρεί όλα τα υδατογραφήματα στη συλλογή από το έγγραφο.

Μάθετε περισσότερα για την αφαίρεση υδατογραφιών στην τεκμηρίωση του GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | Η συλλογή των υδατογραφιών προς αφαίρεση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Αφαιρέστε με αντίστροφη σειρά για να διατηρήσετε τους δείκτες έγκυρους
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
