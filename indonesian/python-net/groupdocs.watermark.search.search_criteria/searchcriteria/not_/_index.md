---
title: "metode not_"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Membalikkan SearchCriteria ini."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

Membalikkan SearchCriteria ini.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### Contoh

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

### Lihat Juga
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
