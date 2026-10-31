---
title: "Kelas WordProcessingTextEffects"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili efek yang dapat diterapkan pada watermark teks untuk dokumen Word."
type: docs
url: /id/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/
is_root: false
weight: 80
---


## WordProcessingTextEffects class

Mewakili efek yang dapat diterapkan pada watermark teks untuk dokumen Word.

Tipe WordProcessingTextEffects menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/__init__/) | Menginisialisasi instance baru dari kelas [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [flip_orientation](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/flip_orientation/) | Orientasi sebuah bentuk. |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | Pengaturan format garis, direpresentasikan oleh sebuah instance [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (diturunkan dari [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/default/) | Mendapatkan nilai default untuk kelas. |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.word_processing as gwo_wp
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_wp.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))

    effects = gwo_wp.WordProcessingTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1

    options = gwo_wp.WordProcessingWatermarkSectionOptions()
    options.effects = effects

    watermarker.add(watermark, options)
    watermarker.save("output.docx")
```

### Lihat Juga
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
