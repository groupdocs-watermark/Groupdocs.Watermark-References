---
title: "Kelas SpreadsheetTextEffects"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili efek yang dapat diterapkan pada watermark teks untuk dokumen Excel."
type: docs
url: /id/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/
is_root: false
weight: 80
---


## SpreadsheetTextEffects class

Mewakili efek yang dapat diterapkan pada watermark teks untuk dokumen Excel.

Tipe SpreadsheetTextEffects menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/) | Menginisialisasi instance baru dari kelas [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | Pengaturan format garis, direpresentasikan oleh sebuah instance [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (diturunkan dari [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Segoe UI", 19.0))
    effects = gwo_xls.SpreadsheetTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1
    options = gwo_xls.SpreadsheetWatermarkShapeOptions()
    options.effects = effects
    watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Lihat Juga
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
