---
title: "método not_"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Niega este SearchCriteria."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

Niega este SearchCriteria.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### Ejemplo

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

### Ver también
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
