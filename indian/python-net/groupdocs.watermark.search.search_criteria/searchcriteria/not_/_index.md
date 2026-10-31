---
title: "not_ मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "इस SearchCriteria को नकारता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

इस SearchCriteria को नकारता है।

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### उदाहरण

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

### संबंधित देखें
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
