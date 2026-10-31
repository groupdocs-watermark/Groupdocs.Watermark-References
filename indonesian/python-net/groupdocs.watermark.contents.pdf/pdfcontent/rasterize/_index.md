---
title: "metode rasterize"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengonversi semua halaman konten menjadi gambar."
type: docs
url: /id/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Mengonversi semua halaman konten menjadi gambar.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| horizontal_resolution | `int` | Resolusi gambar horizontal. |
| vertical_resolution | `int` | Resolusi gambar vertikal. |
| image_format | `PdfImageConversionFormat` | Format gambar. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Tambahkan watermark (opsional)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Rasterize setiap halaman pada 100x100 DPI menjadi gambar PNG
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Lihat Juga
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
