---
title: or_ method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Combines this SearchCriteria with other criteria using the logical OR operator."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Combines this SearchCriteria with other criteria using the logical OR operator.

```python
def or_(self, other):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| other | `SearchCriteria` | Search criteria to combine with. |

**Returns:** SearchCriteria: Combined search criteria.

### Example

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

### See Also
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
