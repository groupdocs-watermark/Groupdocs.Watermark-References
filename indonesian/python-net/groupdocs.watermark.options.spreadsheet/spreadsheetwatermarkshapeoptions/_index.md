---
title: "Kelas SpreadsheetWatermarkShapeOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi saat menambahkan watermark bentuk ke lembar kerja Spreadsheet."
type: docs
url: /id/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
is_root: false
weight: 120
---


## SpreadsheetWatermarkShapeOptions class

Mewakili opsi saat menambahkan watermark bentuk ke lembar kerja Spreadsheet.

Pelajari lebih lanjut:
- Add watermarks to spreadsheet documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

Tipe SpreadsheetWatermarkShapeOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/__init__/) | Menginisialisasi instance baru dari kelas SpreadsheetWatermarkShapeOptions. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [effects](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects/) | Efek yang diterapkan pada watermark, ditentukan sebagai instance [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) atau [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/). |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheet_index/) | Indeks lembar kerja tempat menambahkan watermark. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | Teks deskriptif (alternatif) yang akan dikaitkan dengan sebuah bentuk. (diturunkan dari [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | Properti ini menunjukkan apakah penyuntingan bentuk di Excel dilarang. (diturunkan dari [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | Nama bentuk. (diturunkan dari [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Mendapatkan nilai default untuk kelas. (diturunkan dari [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.spreadsheet import (
    SpreadsheetLoadOptions, SpreadsheetWatermarkShapeOptions,
)

def add_watermark_to_worksheet():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = SpreadsheetWatermarkShapeOptions()
        options.worksheet_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.xlsx")
```

### Lihat Juga
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
