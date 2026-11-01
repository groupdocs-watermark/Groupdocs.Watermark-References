---
title: "and_ yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bu SearchCriteria'yi diğer kriterlerle mantıksal VE operatörü kullanarak birleştirir."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Bu SearchCriteria'yi diğer kriterlerle mantıksal VE operatörü kullanarak birleştirir.

```python
def and_(self, other):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | `SearchCriteria` | Birleştirilecek arama kriteri. |

**Returns:** Combined search criteria.

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Kriterleri birleştir: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Ayrıca Bakınız
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
