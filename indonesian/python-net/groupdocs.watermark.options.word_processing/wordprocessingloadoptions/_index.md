---
title: "Kelas WordProcessingLoadOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi pemuatan dokumen untuk dokumen Word."
type: docs
url: /id/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Mewakili opsi pemuatan dokumen untuk dokumen Word.

Tipe WordProcessingLoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Menginisialisasi sebuah instance baru dari kelas [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Menginisialisasi sebuah instance baru dari kelas WordProcessingLoadOptions dengan kata sandi yang ditentukan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Tipe file, menunjukkan formatnya (mis., docx, pdf, xlsx, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Keluarga format dokumen, menunjukkan jenisnya (mis., Image, Pdf, Spreadsheet, dll.). (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Kata sandi untuk membuka dokumen terenkripsi. (diturunkan dari [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Mendapatkan nilai default untuk kelas. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # melakukan operasi pada konten, misalnya melindungi, membuka perlindungan, menambahkan watermark
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Lihat Juga
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
