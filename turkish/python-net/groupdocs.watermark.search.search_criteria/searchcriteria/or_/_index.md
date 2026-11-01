---
title: "or_ yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bu SearchCriteria'yi diğer kriterlerle mantıksal VEYA operatörü kullanarak birleştirir."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Bu SearchCriteria'yi diğer kriterlerle mantıksal VEYA operatörü kullanarak birleştirir.

```python
def or_(self, other):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | `SearchCriteria` | Birleştirilecek arama kriteri. |

**Returns:** SearchCriteria: Combined search criteria.

### Örnek

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

### Ayrıca Bakınız
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
