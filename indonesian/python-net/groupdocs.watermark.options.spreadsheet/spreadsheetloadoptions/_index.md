---
title: "Kelas SpreadsheetLoadOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi pemuatan dokumen untuk dokumen Spreadsheet."
type: docs
url: /id/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Mewakili opsi pemuatan dokumen untuk dokumen Spreadsheet.

Tipe SpreadsheetLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Menginisialisasi sebuah instance baru dari kelas [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Menginisialisasi sebuah instance baru dari kelas [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) dengan kata sandi yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Tipe file, menunjukkan formatnya (mis., docx, pdf, xlsx, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Keluarga format dokumen, menunjukkan jenisnya (mis., Image, Pdf, Spreadsheet, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Kata sandi untuk membuka dokumen terenkripsi. (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Mendapatkan nilai default untuk kelas. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # lakukan operasi watermark di sini
    pass
```

### Lihat Juga
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
