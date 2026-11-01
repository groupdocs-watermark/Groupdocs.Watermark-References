---
title: "and_-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Kombinerar detta SearchCriteria med andra kriterier med hjälp av den logiska OCH-operatorn."
type: docs
url: /sv/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Kombinerar detta SearchCriteria med andra kriterier med hjälp av den logiska OCH-operatorn.

```python
def and_(self, other):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | `SearchCriteria` | Sök kriterier att kombinera med. |

**Returns:** Combined search criteria.

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Kombinera kriterier: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Se även
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
