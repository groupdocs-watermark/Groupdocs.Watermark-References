---
title: "μέθοδος or_"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Συνδυάζει αυτό το SearchCriteria με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή OR."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Συνδυάζει αυτό το SearchCriteria με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή OR.

```python
def or_(self, other):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | `SearchCriteria` | Κριτήρια αναζήτησης για συνδυασμό. |

**Returns:** SearchCriteria: Combined search criteria.

### Παράδειγμα

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import (
        ImageDctHashSearchCriteria,
        TextSearchCriteria,
    )

    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        combined = image_criteria.or_(text_criteria)
        results = watermarker.search(combined)
        print(f"Found {len(results)} possible watermark(s)")
    ```

### Δείτε επίσης
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
