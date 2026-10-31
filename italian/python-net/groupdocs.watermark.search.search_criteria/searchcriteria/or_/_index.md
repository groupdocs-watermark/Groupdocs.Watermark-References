---
title: "metodo **or_**"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Combina questo SearchCriteria con altri criteri usando l'operatore logico OR."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Combina questo SearchCriteria con altri criteri usando l'operatore logico OR.

```python
def or_(self, other):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | `SearchCriteria` | Criteri di ricerca da combinare con. |

**Returns:** SearchCriteria: Combined search criteria.

### Esempio

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

### Vedi anche
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
