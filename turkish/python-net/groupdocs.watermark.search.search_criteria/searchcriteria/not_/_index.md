---
title: "not_ yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bu SearchCriteria'yi olumsuzlar."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

Bu SearchCriteria'yi olumsuzlar.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### Örnek

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

### Ayrıca Bakınız
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
