---
title: "or_-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Kombinerar detta SearchCriteria med andra kriterier med hjälp av den logiska ELLER-operatorn."
type: docs
url: /sv/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Kombinerar detta SearchCriteria med andra kriterier med hjälp av den logiska ELLER-operatorn.

```python
def or_(self, other):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | `SearchCriteria` | Sök kriterier att kombinera med. |

**Returns:** SearchCriteria: Combined search criteria.

### Exempel

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

### Se även
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
