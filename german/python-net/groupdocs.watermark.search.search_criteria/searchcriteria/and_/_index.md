---
title: "and_ Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Kombiniert dieses SearchCriteria mit anderen Kriterien mithilfe des logischen UND‑Operators."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Kombiniert dieses SearchCriteria mit anderen Kriterien mithilfe des logischen UND‑Operators.

```python
def and_(self, other):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | `SearchCriteria` | Suchkriterien zum Kombinieren mit. |

**Returns:** Combined search criteria.

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Kombiniere Kriterien: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Siehe auch
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
