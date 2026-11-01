---
title: "método and_"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Combina este SearchCriteria con otros criterios usando el operador lógico AND."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Combina este SearchCriteria con otros criterios usando el operador lógico AND.

```python
def and_(self, other):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | `SearchCriteria` | Criterio de búsqueda para combinar. |

**Returns:** Combined search criteria.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Combinar criterios: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Ver también
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
