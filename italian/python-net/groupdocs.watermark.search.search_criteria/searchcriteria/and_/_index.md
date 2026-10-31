---
title: "metodo **and_**"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Combina questo SearchCriteria con altri criteri usando l'operatore logico AND."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Combina questo SearchCriteria con altri criteri usando l'operatore logico AND.

```python
def and_(self, other):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | `SearchCriteria` | Criteri di ricerca da combinare con. |

**Returns:** Combined search criteria.

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Combina criteri: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Vedi anche
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
