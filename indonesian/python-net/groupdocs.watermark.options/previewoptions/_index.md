---
title: "Kelas PreviewOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau."
type: docs
url: /id/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Menyediakan opsi untuk mengatur persyaratan dan delegasi aliran untuk pembuatan pratinjau.

Tipe PreviewOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Menginisialisasi sebuah instance PreviewOptions baru yang menutup aliran keluaran setelah digunakan. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Menginisialisasi sebuah instance PreviewOptions baru yang mengembalikan aliran keluaran ke klien untuk penggunaan lebih lanjut. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Delegate pembuatan aliran halaman yang digunakan untuk memperoleh aliran yang dapat ditulis untuk setiap halaman yang dirender. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Tinggi pratinjau halaman. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Array nomor halaman untuk menghasilkan pratinjau. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Format gambar pratinjau. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Delegate penyelesaian pratinjau halaman. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Lebar pratinjau halaman. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Sediakan aliran file yang dapat ditulis untuk setiap halaman yang akan dirender
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
Panduan tugas yang menggunakan `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### Lihat Juga
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
