---
title: "and_ methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Combineert deze SearchCriteria met andere criteria met behulp van de logische EN‑operator."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Combineert deze SearchCriteria met andere criteria met behulp van de logische EN‑operator.

```python
def and_(self, other):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | `SearchCriteria` | Zoekcriteria om mee te combineren. |

**Returns:** Combined search criteria.

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Combineer criteria: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Zie ook
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
