---
title: "método or_"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Combina este SearchCriteria con otros criterios usando el operador lógico OR."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Combina este SearchCriteria con otros criterios usando el operador lógico OR.

```python
def or_(self, other):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | `SearchCriteria` | Criterio de búsqueda para combinar. |

**Returns:** SearchCriteria: Combined search criteria.

### Ejemplo

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import (
        ImageDctHashSearchCriteria,
        TextSearchCriteria,
    )

    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        combined = image_criteria.or_(text_criteria)
        results = watermarker.search(combined)
        print(f"Found {len(results)} possible watermark(s)")
    ```

### Ver también
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
