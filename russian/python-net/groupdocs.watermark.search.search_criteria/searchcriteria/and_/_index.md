---
title: "and_ метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Объединяет этот SearchCriteria с другими критериями с помощью логического оператора И (AND)."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Объединяет этот SearchCriteria с другими критериями с помощью логического оператора И (AND).

```python
def and_(self, other):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | `SearchCriteria` | Критерий поиска для комбинирования. |

**Returns:** Combined search criteria.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Комбинировать критерии: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### См. также
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
