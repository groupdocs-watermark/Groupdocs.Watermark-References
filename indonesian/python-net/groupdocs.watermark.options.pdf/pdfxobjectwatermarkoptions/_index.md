---
title: "Kelas PdfXObjectWatermarkOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi penambahan watermark saat menambahkan watermark XObject ke dokumen PDF."
type: docs
url: /id/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
is_root: false
weight: 70
---


## PdfXObjectWatermarkOptions class

Mewakili opsi penambahan watermark saat menambahkan watermark XObject ke dokumen PDF.

Pelajari lebih lanjut:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Tipe PdfXObjectWatermarkOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/__init__/) | Menginisialisasi instance baru dari kelas [`PdfXObjectWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/page_index/) | Indeks halaman tempat menambahkan watermark. |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Mendapatkan nilai default untuk kelas. (diturunkan dari [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfXObjectWatermarkOptions
from groupdocs.watermark.watermarks import ImageWatermark

load_options = PdfLoadOptions()
with Watermarker("./document.pdf", load_options) as watermarker:
    with ImageWatermark("./logo.png") as watermark:
        options = PdfXObjectWatermarkOptions()
        options.page_index = 0  # apply to the first page
        watermarker.add(watermark, options)
    watermarker.save("./output.pdf")
```

### Lihat Juga
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
