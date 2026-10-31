---
title: "μέθοδος search"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης."
type: docs
url: /el/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Τα κριτήρια αναζήτησης προς χρήση. |

**Returns:** The collection of the possible watermarks.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Βρίσκει όλα τα πιθανά υδατογραφήματα στο περιεχόμενο.

Η αναζήτηση γίνεται στα αντικείμενα που καθορίζονται στο [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Δείτε επίσης
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
