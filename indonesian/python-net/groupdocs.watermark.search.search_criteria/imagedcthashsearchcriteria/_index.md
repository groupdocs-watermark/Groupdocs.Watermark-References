---
title: "Kelas ImageDctHashSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili kriteria pencarian untuk menemukan gambar dalam dokumen."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

Mewakili kriteria pencarian untuk menemukan gambar dalam dokumen.

Kriteria pencarian ini menggunakan hash gambar perseptual berbasis DCT untuk menghitung kemiripan gambar. Pelajari lebih lanjut: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Tipe ImageDctHashSearchCriteria menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | Menginisialisasi instance ImageDctHashSearchCriteria baru dengan jalur file yang ditentukan. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | Menginisialisasi instance ImageDctHashSearchCriteria baru dengan aliran gambar yang disediakan. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | Perbedaan maksimum yang diizinkan antara gambar. (diturunkan dari [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | Daftar nomor halaman tertentu. (diturunkan dari [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
Panduan tugas yang menggunakan `ImageDctHashSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Lihat Juga
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
