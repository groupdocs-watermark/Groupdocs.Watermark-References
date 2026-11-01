---
title: "or_ methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Combineert deze SearchCriteria met andere criteria met behulp van de logische OF‑operator."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Combineert deze SearchCriteria met andere criteria met behulp van de logische OF‑operator.

```python
def or_(self, other):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | `SearchCriteria` | Zoekcriteria om mee te combineren. |

**Returns:** SearchCriteria: Combined search criteria.

### Voorbeeld

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

### Zie ook
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
