---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas ColorRange."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari kelas [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Buat rentang warna default
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

Menginisialisasi sebuah instance baru dari [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) dengan warna tepat yang ditentukan.

```python
def __init__(self, exact_color):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| exact_color | `Color` | Warna tepat dari mana rentang dibuat. |

### Lihat Juga
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
