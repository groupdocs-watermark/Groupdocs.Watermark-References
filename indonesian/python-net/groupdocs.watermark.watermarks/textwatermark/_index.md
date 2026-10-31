---
title: "Kelas TextWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili watermark teks."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Mewakili watermark teks.

Pelajari lebih lanjut:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

Tipe TextWatermark menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Menginisialisasi TextWatermark baru dengan teks dan font yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | Warna latar belakang teks. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | Font teks. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | Warna latar depan teks. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | Pengaturan padding dari TextWatermark ini, hanya berlaku untuk file gambar. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | Teks yang akan digunakan sebagai watermark. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | Perataan teks watermark. |
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Panduan tugas yang menggunakan `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
