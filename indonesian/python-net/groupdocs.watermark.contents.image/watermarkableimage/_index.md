---
title: "Kelas WatermarkableImage"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili gambar di dalam dokumen."
type: docs
url: /id/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Mewakili gambar di dalam dokumen.

Pelajari lebih lanjut:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

Tipe WatermarkableImage menampilkan anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Menambahkan watermark ke [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) ini. Metode ini mengasumsikan bahwa offset dan ukuran watermark diukur dalam piksel (jika telah ditetapkan). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Mendapatkan gambar sebagai array byte. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang tercantum dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Tinggi [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) ini dalam piksel. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Lebar WatermarkableImage ini dalam piksel. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Inisialisasi watermark teks.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Temukan semua gambar dalam dokumen.
    images = watermarker.get_images()

    # Tambahkan watermark ke setiap gambar.
    for img in images:
        img.add(watermark)

    # Simpan perubahan.
    watermarker.save(r"D:\output.doc")
```

### Lihat Juga
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
