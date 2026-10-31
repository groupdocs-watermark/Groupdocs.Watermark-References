---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi sebuah instance PreviewOptions baru yang menutup aliran keluaran setelah digunakan."
type: docs
url: /id/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Menginisialisasi sebuah instance PreviewOptions baru yang menutup aliran keluaran setelah digunakan.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Membuat aliran untuk pratinjau halaman tertentu. |

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

## __init__ {#create_page_stream-release_page_stream}

Menginisialisasi sebuah instance PreviewOptions baru yang mengembalikan aliran keluaran ke klien untuk penggunaan lebih lanjut.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable yang membuat aliran untuk pratinjau halaman tertentu. Menerima nomor halaman (`int`) dan harus mengembalikan aliran yang dapat ditulisi (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable yang dipanggil ketika pembuatan pratinjau halaman selesai dan menyediakan aliran output. |

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

### Lihat Juga
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
