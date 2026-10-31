---
title: "طريقة and_"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل AND المنطقي."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل AND المنطقي.

```python
def and_(self, other):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | `SearchCriteria` | معايير البحث للدمج معها. |

**Returns:** Combined search criteria.

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # دمج المعايير: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### انظر أيضًا
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
