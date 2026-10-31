---
title: "Kelas RotateAngleSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan sudut rotasi watermark."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

Mewakili kriteria yang memungkinkan penyaringan berdasarkan sudut rotasi watermark.

Pelajari lebih lanjut:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Tipe RotateAngleSearchCriteria menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | Menginisialisasi RotateAngleSearchCriteria baru dengan sudut awal dan sudut akhir. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Menggabungkan SearchCriteria ini dengan kriteria lain menggunakan operator logika AND. (diturunkan dari [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (diturunkan dari [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Membalikkan SearchCriteria ini. (diturunkan dari [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Menggabungkan SearchCriteria ini dengan kriteria lain menggunakan operator logika OR. (diturunkan dari [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (diturunkan dari [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | Sudut akhir dalam derajat. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | Sudut awal dalam derajat. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
Panduan tugas yang menggunakan `RotateAngleSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
