---
title: "méthode not_"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Négate ce SearchCriteria."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

Négate ce SearchCriteria.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### Exemple

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

### Voir aussi
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
