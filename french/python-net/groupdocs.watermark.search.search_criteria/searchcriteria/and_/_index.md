---
title: "méthode and_"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Combine ce SearchCriteria avec d'autres critères en utilisant l'opérateur logique ET."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Combine ce SearchCriteria avec d'autres critères en utilisant l'opérateur logique ET.

```python
def and_(self, other):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| other | `SearchCriteria` | Critères de recherche à combiner avec. |

**Returns:** Combined search criteria.

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Combiner les critères : (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Voir aussi
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
