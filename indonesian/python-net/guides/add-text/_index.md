---
title: "Tambahkan watermark teks"
linkTitle: "Add text watermarks"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Artikel ini menunjukkan cara menambahkan watermark teks ke dokumen dan menyimpan hasilnya dengan GroupDocs.Watermark untuk Python via .NET."
type: docs
url: /id/python-net/guides/add-text/
is_root: false
weight: 40
---


Salah satu fitur utama GroupDocs.Watermark adalah menambahkan watermark teks ke dokumen. Anda dapat menambahkan watermark ke dokumen atau gambar dari jalur lokal, serta dari aliran. Untuk daftar lengkap format yang didukung, periksa [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Untuk menambahkan watermark teks, ikuti langkah-langkah berikut:

1. Buka dokumen dengan memberikan jalurnya (atau aliran) ke kelas [Watermarker](https://reference.groupdocs.com/watermark/python-net/) menggunakan blok `with` sehingga dokumen dilepaskan secara otomatis.
2. Buat sebuah [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) dengan teks yang diinginkan dan [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Gaya watermark — misalnya, atur `foreground_color` dan perataan.
4. Panggil `add()` untuk menerapkan watermark dan `save()` untuk menulis hasilnya.

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Bangun watermark teks dan beri gaya
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Jalankan program. Dokumen berwatermark baru muncul di jalur yang ditentukan.

## What's next

GroupDocs.Watermark menawarkan banyak kemampuan tambahan untuk watermark teks — warna latar belakang dan latar depan, font khusus, opasitas, rotasi, penataan ubin, serta penempatan absolut atau relatif. Lihat [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) dalam panduan lanjutan.
