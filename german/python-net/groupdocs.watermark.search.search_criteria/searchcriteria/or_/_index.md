---
title: "or_ Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Kombiniert dieses SearchCriteria mit anderen Kriterien mithilfe des logischen ODER‑Operators."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Kombiniert dieses SearchCriteria mit anderen Kriterien mithilfe des logischen ODER‑Operators.

```python
def or_(self, other):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | `SearchCriteria` | Suchkriterien zum Kombinieren mit. |

**Returns:** SearchCriteria: Combined search criteria.

### Beispiel

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

### Siehe auch
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
