---
title: "Kelas SpreadsheetImageEffects"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili efek yang dapat diterapkan pada watermark gambar untuk dokumen Excel."
type: docs
url: /id/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Mewakili efek yang dapat diterapkan pada watermark gambar untuk dokumen Excel.

Tipe SpreadsheetImageEffects menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | Menginisialisasi instance baru dari kelas [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Pengaturan format garis untuk batas gambar. (diturunkan dari [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | Kecerahan gambar. Harus berupa float antara 0.0 (paling gelap) dan 1.0 (paling terang). Nilai default adalah 0.5. (diturunkan dari [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Nilai warna gambar yang akan diperlakukan sebagai transparan. Nilai default adalah warna yang sepenuhnya transparan. (diturunkan dari [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Kontras untuk gambar yang ditentukan. Harus berupa float antara 0.0 (kontras terendah) dan 1.0 (kontras tertinggi). Nilai default adalah 0.5. (diturunkan dari [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | Properti ini menunjukkan apakah gambar akan ditampilkan dalam mode skala abu-abu. (diturunkan dari [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_xls.SpreadsheetImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1
        options = gwo_xls.SpreadsheetWatermarkShapeOptions()
        options.effects = effects
        watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Lihat Juga
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
