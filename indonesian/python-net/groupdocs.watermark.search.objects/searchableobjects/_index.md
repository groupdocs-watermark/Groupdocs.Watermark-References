---
title: "Kelas SearchableObjects"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menentukan objek dokumen yang akan dimasukkan dalam pencarian watermark."
type: docs
url: /id/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Menentukan objek dokumen yang akan dimasukkan dalam pencarian watermark.

Pelajari lebih lanjut:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Tipe SearchableObjects menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Menginisialisasi instance baru dari kelas [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Objek-objek di dalam dokumen Visio yang akan dimasukkan dalam pencarian watermark. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Objek-objek di dalam pesan email yang akan dimasukkan dalam pencarian watermark. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Objek-objek di dalam dokumen PDF yang akan dimasukkan dalam pencarian watermark. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Objek-objek di dalam dokumen PowerPoint yang akan dimasukkan dalam pencarian watermark. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Objek-objek di dalam dokumen Excel yang akan dimasukkan dalam pencarian watermark. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Objek-objek di dalam dokumen Word yang akan dimasukkan dalam pencarian watermark. |

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
Panduan tugas yang menggunakan `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
