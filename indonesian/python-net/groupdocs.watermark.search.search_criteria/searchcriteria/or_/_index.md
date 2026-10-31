---
title: "metode or_"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menggabungkan SearchCriteria ini dengan kriteria lain menggunakan operator logika OR."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Menggabungkan SearchCriteria ini dengan kriteria lain menggunakan operator logika OR.

```python
def or_(self, other):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | `SearchCriteria` | Kriteria pencarian untuk digabungkan dengan. |

**Returns:** SearchCriteria: Combined search criteria.

### Contoh

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

### Lihat Juga
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
