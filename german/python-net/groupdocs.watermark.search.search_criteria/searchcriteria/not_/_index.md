---
title: "not_ Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Negiert dieses SearchCriteria."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

Negiert dieses SearchCriteria.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### Beispiel

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

### Siehe auch
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
