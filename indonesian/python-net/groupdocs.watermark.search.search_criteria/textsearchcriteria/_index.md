---
title: "Kelas TextSearchCriteria"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili kriteria yang memungkinkan penyaringan berdasarkan teks watermark."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

Mewakili kriteria yang memungkinkan penyaringan berdasarkan teks watermark.

Pelajari lebih lanjut:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Tipe TextSearchCriteria menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | Menginisialisasi TextSearchCriteria baru dengan ekspresi reguler yang ditentukan. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) dengan string pencarian dan flag untuk perbandingan yang sensitif huruf. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | Menginisialisasi instance baru dari kelas [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) dengan string pencarian. |

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
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | Pola ekspresi reguler untuk dicocokkan. |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | Properti yang menunjukkan apakah karakter yang tidak dapat dibaca dilewati selama perbandingan string. |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | Daftar nomor halaman tertentu. (diturunkan dari [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Guides
Panduan tugas yang menggunakan `TextSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Lihat Juga
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
