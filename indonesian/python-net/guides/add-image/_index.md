---
title: "Tambahkan watermark gambar"
linkTitle: "Add image watermarks"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Artikel ini menunjukkan cara menambahkan watermark gambar ke sebuah dokumen dan menyimpan hasilnya dengan GroupDocs.Watermark untuk Python melalui .NET."
type: docs
url: /id/python-net/guides/add-image/
is_root: false
weight: 50
---


Salah satu fitur utama GroupDocs.Watermark adalah menambahkan watermark gambar ke dokumen. Anda dapat menambahkan watermark ke dokumen atau gambar dari jalur lokal, serta dari aliran. Untuk daftar lengkap format yang didukung, periksa [Format dokumen yang didukung](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Untuk menambahkan watermark gambar, ikuti langkah-langkah berikut:

1. Buka dokumen dengan memberikan jalurnya (atau aliran) ke kelas [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) .
2. Buat sebuah [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) dari file gambar watermark (atau aliran).
3. Tempatkan watermark — misalnya, atur `horizontal_alignment`, `vertical_alignment`, dan `opacity`.
4. Panggil `add()` untuk menerapkan watermark dan `save()` untuk menulis hasilnya.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Buat watermark gambar dari file logo dan letakkan di tengah
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` dan `logo.png` adalah file contoh yang digunakan dalam contoh ini. Unduh [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) dan [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark menawarkan lebih banyak kemampuan untuk watermark gambar — memuat dari aliran, skala, penataan ubin, dan penempatan absolut atau relatif. Lihat [Menambahkan watermark gambar](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) dalam panduan lanjutan.
