---
title: "μέθοδος search"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναζητά όλα τα πιθανά υδατογραφήματα στο έγγραφο."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Αναζητά όλα τα πιθανά υδατογραφήματα στο έγγραφο.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται στο [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Μάθετε περισσότερα για την αναζήτηση υδατοσημάτων https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

## search {#search_criteria}

Αναζητά πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται στο [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Μάθετε περισσότερα για την αναζήτηση υδατοσημάτων: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Τα κριτήρια αναζήτησης προς χρήση. |

**Returns:** The collection of possible watermarks.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
