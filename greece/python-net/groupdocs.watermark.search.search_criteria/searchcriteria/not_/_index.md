---
title: "μέθοδος not_"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιστρέφει αυτό το SearchCriteria."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

Αντιστρέφει αυτό το SearchCriteria.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_not():
    with Watermarker("./document.pdf") as watermarker:
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        not_criteria = text_criteria.not_()
        results = watermarker.search(not_criteria)
        print("Found", len(results), "watermarks that do NOT match the text")
```

### Δείτε επίσης
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
