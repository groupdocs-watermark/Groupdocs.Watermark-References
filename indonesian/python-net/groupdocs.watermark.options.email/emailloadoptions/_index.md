---
title: "Kelas EmailLoadOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi pemuatan dokumen untuk pesan email."
type: docs
url: /id/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Mewakili opsi pemuatan dokumen untuk pesan email.

Tipe EmailLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Menginisialisasi instance baru dari kelas [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Tipe file, menunjukkan formatnya (mis., docx, pdf, xlsx, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Keluarga format dokumen, menunjukkan jenisnya (mis., Image, Pdf, Spreadsheet, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Kata sandi untuk membuka dokumen terenkripsi. (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Mendapatkan nilai default untuk kelas. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # manipulasi konten email di sini
    watermarker.save("./output.msg")
```

### Lihat Juga
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
