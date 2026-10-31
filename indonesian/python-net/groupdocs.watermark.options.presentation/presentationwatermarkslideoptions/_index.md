---
title: "Kelas PresentationWatermarkSlideOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi saat menambahkan watermark ke slide dokumen Presentation."
type: docs
url: /id/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
is_root: false
weight: 140
---


## PresentationWatermarkSlideOptions class

Mewakili opsi saat menambahkan watermark ke slide dokumen Presentation.

Pelajari lebih lanjut:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Tipe PresentationWatermarkSlideOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/) | Menginisialisasi instance baru dari kelas [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slide_index/) | Indeks slide untuk menambahkan watermark. |
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.presentation import (
    PresentationLoadOptions, PresentationWatermarkSlideOptions,
)

def add_watermark_to_slide():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = PresentationWatermarkSlideOptions()
        options.slide_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.pptx")
```

### Lihat Juga
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
