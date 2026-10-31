---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas PdfWatermarkableImage menggunakan data gambar yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Menginisialisasi sebuah instance baru dari kelas [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) menggunakan data gambar yang ditentukan.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_data | `list[int]` | Array byte tak bertanda dari mana membuat `PdfWatermarkableImage`. |

### Contoh

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Lihat Juga
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
