---
title: "Pratinjau dokumen"
linkTitle: "Document preview"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Hasilkan gambar pratinjau (PNG/JPG/BMP) untuk halaman dokumen menggunakan GroupDocs.Watermark untuk Python melalui .NET."
type: docs
url: /id/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark dapat merender halaman dokumen sebagai gambar sehingga Anda dapat menampilkan thumbnail halaman tanpa harus membuka dokumen sepenuhnya di penampil. Anda mengendalikan render dengan callback `create_page_stream` yang menyediakan aliran file yang dapat ditulis untuk setiap halaman — perpustakaan menulis gambar halaman ke aliran tersebut dan menutupnya untuk Anda.

## Generate a document preview

Setel [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) dengan callback `create_page_stream`, pilih `preview_format`, dan daftarkan `page_numbers` yang akan dirender.

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
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
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh dua halaman yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Gambar halaman ditulis ke direktori saat ini — satu PNG per halaman yang diminta. Gunakan `PreviewFormats.JPEG` atau `PreviewFormats.BMP` untuk format lain, dan atur `options.width` / `options.height` untuk mengontrol ukuran hasil render.

Perpustakaan menutup setiap file yang dikembalikan oleh `create_page_stream` setelah halaman selesai ditulis. Untuk menangani halaman segera setelah siap, berikan callback kedua: `PreviewOptions(create_page_stream, release_page_stream)` memanggil `release_page_stream(page_number, stream)` dengan objek yang dikembalikan oleh `create_page_stream` untuk halaman tersebut, setelah seluruh gambar berada di dalamnya. Callback satu argumen `release_page_stream(page_number)` juga berfungsi. `create_page_stream` juga dapat mengembalikan `io.BytesIO`: tetap terbuka, dan menahan gambar halaman sampai `release_page_stream` mengambilnya.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
