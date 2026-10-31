---
title: "Kelas ImageWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili watermark gambar."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Mewakili watermark gambar.

Pelajari lebih lanjut:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

Tipe ImageWatermark menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Menginisialisasi instance ImageWatermark baru dengan jalur file yang ditentukan. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Menginisialisasi ImageWatermark baru dengan aliran gambar yang disediakan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Membuang instance saat ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | Properti yang menunjukkan apakah ukuran dan koordinat watermark dihitung dengan mempertimbangkan margin induk. Jika diatur ke True, perhitungan mempertimbangkan margin induk; secara default nilai adalah False dan margin induk diabaikan. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | Tinggi yang diinginkan untuk [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) ini. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | Perataan horizontal dari Watermark ini. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | Properti yang menunjukkan apakah watermark harus ditempatkan di latar belakang. Jika true, watermark ditempatkan di bagian bawah; jika tidak, ditempatkan di bagian atas (default adalah False). (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Pengaturan margin dari Watermark ini. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | Kejernihan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Pengaturan penyiapan halaman dari Watermark ini. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | Sudut rotasi dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) dalam derajat. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | Properti ini menunjukkan apakah menyimpan informasi tentang watermark yang ditambahkan dalam metadata dokumen. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Faktor skala dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), yang menentukan bagaimana ukuran watermark bergantung pada ukuran induk. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Jenis ukuran watermark. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Opsi untuk mendefinisikan watermark berulang. (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | Perataan vertikal dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | Lebar yang diinginkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | Koordinat x dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | Koordinat y dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (diturunkan dari [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Contoh

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Muat data gambar ke dalam aliran
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Buka dokumen dan tambahkan watermark gambar
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Panduan tugas yang menggunakan `ImageWatermark`:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Lihat Juga
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
