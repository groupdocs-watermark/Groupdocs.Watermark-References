---
title: "méthode or_"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Combine ce SearchCriteria avec d'autres critères en utilisant l'opérateur logique OU."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Combine ce SearchCriteria avec d'autres critères en utilisant l'opérateur logique OU.

```python
def or_(self, other):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| other | `SearchCriteria` | Critères de recherche à combiner avec. |

**Returns:** SearchCriteria: Combined search criteria.

### Exemple

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

### Voir aussi
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
