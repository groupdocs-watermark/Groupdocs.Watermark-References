---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi RotateAngleSearchCriteria baru dengan sudut awal dan sudut akhir."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Menginisialisasi RotateAngleSearchCriteria baru dengan sudut awal dan sudut akhir.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| min_angle | `float` | Sudut awal dalam derajat. |
| max_angle | `float` | Sudut akhir dalam derajat. |

### Contoh

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Cari watermark yang diputar antara 30 dan 60 derajat
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Lihat Juga
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
