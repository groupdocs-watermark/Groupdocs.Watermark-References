---
title: "طريقة not_"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينفي هذا SearchCriteria."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

ينفي هذا SearchCriteria.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### مثال

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

### انظر أيضًا
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
