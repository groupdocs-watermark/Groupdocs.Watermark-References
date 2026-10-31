---
title: "Kelas PresentationLoadOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi pemuatan dokumen untuk dokumen Presentation."
type: docs
url: /id/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Mewakili opsi pemuatan dokumen untuk dokumen Presentation.

Tipe PresentationLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Menginisialisasi instance baru dari kelas [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Menginisialisasi instance baru dari kelas PresentationLoadOptions dengan kata sandi yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Tipe file, menunjukkan formatnya (mis., docx, pdf, xlsx, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Keluarga format dokumen, menunjukkan jenisnya (mis., Image, Pdf, Spreadsheet, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Kata sandi untuk membuka dokumen terenkripsi. (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Mendapatkan nilai default untuk kelas. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # bekerja dengan dokumen
    pass
```

### Lihat Juga
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
