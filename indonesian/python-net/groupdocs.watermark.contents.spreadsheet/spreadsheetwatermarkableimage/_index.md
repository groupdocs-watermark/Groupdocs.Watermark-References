---
title: "Kelas SpreadsheetWatermarkableImage"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili gambar di dalam dokumen Excel."
type: docs
url: /id/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/
is_root: false
weight: 230
---


## SpreadsheetWatermarkableImage class

Mewakili gambar di dalam dokumen Excel.

Tipe SpreadsheetWatermarkableImage menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/#image_data) | Menginisialisasi instance baru dari kelas [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) menggunakan data gambar yang ditentukan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Menambahkan watermark ke [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Metode ini mengasumsikan bahwa offset dan ukuran watermark diukur dalam piksel (jika mereka ditetapkan). (diturunkan dari [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (diturunkan dari [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Mendapatkan gambar sebagai array byte. (diturunkan dari [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang tercantum dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Tinggi [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) dalam piksel. (diturunkan dari [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Lebar WatermarkableImage ini dalam piksel. (diturunkan dari [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    img = gwc_xls.SpreadsheetWatermarkableImage(f.read())
# img dapat ditetapkan ke shape.image, latar belakang diagram, dll.
```

### Lihat Juga
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
