---
title: "Kelas WordProcessingWatermarkPagesOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi saat menambahkan watermark ke halaman dokumen Word."
type: docs
url: /id/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/
is_root: false
weight: 110
---


## WordProcessingWatermarkPagesOptions class

Mewakili opsi saat menambahkan watermark ke halaman dokumen Word.

Pelajari lebih lanjut:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

Tipe WordProcessingWatermarkPagesOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/) | Menginisialisasi sebuah instance baru dari kelas WordProcessingWatermarkPagesOptions. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/page_numbers/) | Nomor halaman untuk menambahkan watermark. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. (diturunkan dari [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Efek yang akan diterapkan pada watermark, ditentukan sebagai instance [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) atau [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). (diturunkan dari [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | Properti ini menunjukkan apakah penyuntingan bentuk di Word dilarang. (diturunkan dari [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Tipe kunci watermark. (diturunkan dari [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | Nama bentuk. (diturunkan dari [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | Kata sandi yang digunakan untuk mengunci watermark. (diturunkan dari [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Mendapatkan nilai default untuk kelas. (diturunkan dari [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions, WordProcessingWatermarkPagesOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = WordProcessingLoadOptions()
with Watermarker(r"D:\test.doc", load_options) as watermarker:
    watermark = TextWatermark("text", Font("Arial", 42))
    options = WordProcessingWatermarkPagesOptions()
    options.page_numbers = [1]

    watermarker.add(watermark, options)
    watermarker.save()
```

### Lihat Juga
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
