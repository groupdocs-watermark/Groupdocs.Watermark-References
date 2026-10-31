---
title: "metode and_"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menggabungkan SearchCriteria ini dengan kriteria lain menggunakan operator logika AND."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

Menggabungkan SearchCriteria ini dengan kriteria lain menggunakan operator logika AND.

```python
def and_(self, other):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | `SearchCriteria` | Kriteria pencarian untuk digabungkan dengan. |

**Returns:** Combined search criteria.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # Gabungkan kriteria: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### Lihat Juga
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
