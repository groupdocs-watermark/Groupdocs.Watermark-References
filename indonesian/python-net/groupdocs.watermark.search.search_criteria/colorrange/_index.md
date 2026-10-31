---
title: "Kelas ColorRange"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili rentang warna menggunakan representasi HSB dari warna RGB."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Mewakili rentang warna menggunakan representasi HSB dari warna RGB.

Tipe ColorRange menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Menginisialisasi sebuah instance baru dari kelas [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/). |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Menginisialisasi sebuah instance baru dari [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) dengan warna tepat yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Bendera yang menunjukkan apakah hanya warna kosong yang berada dalam rentang. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Nilai kecerahan akhir, berkisar antara 0.0 (hitam) hingga 1.0 (putih). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Nilai hue akhir, dalam derajat. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Nilai saturasi akhir. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Nilai kecerahan awal, berkisar antara 0.0 (hitam) hingga 1.0 (putih). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Nilai hue awal, dalam derajat. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Nilai saturasi awal. |

### Contoh

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Buat rentang warna untuk pencocokan warna latar depan
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Panduan tugas yang menggunakan `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
