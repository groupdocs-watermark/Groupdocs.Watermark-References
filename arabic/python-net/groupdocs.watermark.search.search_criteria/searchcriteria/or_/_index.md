---
title: "طريقة or_"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل OR المنطقي."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل OR المنطقي.

```python
def or_(self, other):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | `SearchCriteria` | معايير البحث للدمج معها. |

**Returns:** SearchCriteria: Combined search criteria.

### مثال

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

### انظر أيضًا
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
