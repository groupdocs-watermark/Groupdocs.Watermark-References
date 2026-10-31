---
title: "Kelas PresentationWatermarkNoteSlideOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi saat menambahkan watermark ke slide catatan dokumen Presentation."
type: docs
url: /id/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/
is_root: false
weight: 120
---


## PresentationWatermarkNoteSlideOptions class

Mewakili opsi saat menambahkan watermark ke slide catatan dokumen Presentation.

Pelajari lebih lanjut:
- [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

Lihat contoh penggunaan di [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Tipe PresentationWatermarkNoteSlideOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/__init__/) | Menginisialisasi instance baru dari kelas [`PresentationWatermarkNoteSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarknoteslideoptions/slide_index/) | Indeks slide untuk menambahkan watermark ke slide catatan. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. (diturunkan dari [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Efek-efek yang akan diterapkan pada watermark, ditentukan sebagai sebuah instance [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) atau [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). (diturunkan dari [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | Properti ini menunjukkan apakah penyuntingan bentuk di PowerPoint dilarang. (diturunkan dari [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Nama bentuk. (diturunkan dari [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | Properti yang menunjukkan apakah karakter watermark teks dicampur dengan karakter yang tidak dapat dibaca. (diturunkan dari [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Mendapatkan nilai default untuk kelas. (diturunkan dari [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    content = watermarker.get_content()

    note_opts = gwo_ppt.PresentationWatermarkNoteSlideOptions()
    note_opts.slide_index = 0  # index of the slide whose notes will receive the watermark
    watermarker.add(watermark, note_opts)
```

### Lihat Juga
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
