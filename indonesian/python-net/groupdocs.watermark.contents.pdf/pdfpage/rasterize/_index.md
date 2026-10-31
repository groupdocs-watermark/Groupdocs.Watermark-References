---
title: "metode rasterize"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengonversi konten halaman menjadi gambar."
type: docs
url: /id/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Mengonversi konten halaman menjadi gambar.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Rasterkan halaman pertama menjadi gambar PNG pada 100 DPI
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Lihat Juga
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
