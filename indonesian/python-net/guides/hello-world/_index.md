---
title: "Hello, World!"
linkTitle: "Hello, World!"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mulai dengan cepat GroupDocs.Watermark untuk Python via .NET dengan membuat dan menjalankan contoh sederhana."
type: docs
url: /id/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Contoh "Hello, World!" biasanya merupakan langkah pertama saat menjelajahi GroupDocs.Watermark untuk Python via .NET. Ini berfungsi sebagai tes sederhana untuk memastikan lingkungan pengembangan Anda telah disiapkan dengan benar dan perpustakaan berfungsi sebagaimana mestinya.

## Overview
GroupDocs.Watermark untuk Python via .NET memungkinkan Anda menambahkan, mencari, dan menghapus watermark dalam berbagai format dokumen. Berbagai [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) membuatnya serbaguna untuk berbagai kasus penggunaan.

## How to add a watermark
Langkah-langkah berikut menunjukkan cara menambahkan watermark teks ke dokumen menggunakan GroupDocs.Watermark untuk Python via .NET:

1. Impor kelas `groupdocs.watermark` yang Anda perlukan.
2. Buka sebuah [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) dengan path ke dokumen contoh.
3. Buat sebuah [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) dengan teks dan font yang diinginkan, serta atur gayanya.
4. Terapkan watermark dengan `add()`.
5. Simpan hasilnya.

## Complete example
Contoh di bawah menambahkan watermark teks "Hello, Watermark!" yang semi-transparan dan diagonal, lalu menyimpan hasilnya:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Buka dokumen, tambahkan satu watermark teks, dan simpan hasilnya
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Watermark disimpan kembali ke format PDF yang sama seperti `output.pdf`. Untuk menandai dokumen lain, ubah path input dan ekstensi output — GroupDocs.Watermark menyimpan dalam format dokumen input.

## Additional resources
Demo ini merujuk pada [contoh kode](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) GroupDocs.Watermark untuk Python via .NET.
