---
title: "Kelas PdfWatermarkableImage"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili gambar di dalam dokumen Pdf."
type: docs
url: /id/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
is_root: false
weight: 240
---


## PdfWatermarkableImage class

Mewakili gambar di dalam dokumen Pdf.

Tipe PdfWatermarkableImage menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/#image_data) | Menginisialisasi sebuah instance baru dari kelas [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) menggunakan data gambar yang ditentukan. |

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
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Lihat Juga
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
