---
title: "Kelas WatermarkerSettings"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku Watermarker."
type: docs
url: /id/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Mendefinisikan pengaturan untuk menyesuaikan perilaku Watermarker.

Tipe WatermarkerSettings menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Menginisialisasi instance baru dari WatermarkerSettings. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Logger yang digunakan untuk mencatat peristiwa dan kesalahan selama watermarking. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Objek yang dapat dicari yang akan dimasukkan dalam pencarian watermark. |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Mendapatkan nilai default untuk kelas. |

### Contoh

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
Panduan tugas yang menggunakan `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
