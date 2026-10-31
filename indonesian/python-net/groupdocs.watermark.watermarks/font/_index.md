---
title: "Kelas Font"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili sebuah font."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Mewakili sebuah font.

Tipe Font menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Menginisialisasi instance Font baru dengan nama keluarga font dan ukuran yang ditentukan. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Menginisialisasi instance Font baru dengan nama keluarga font, ukuran, dan gaya yang ditentukan. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Menginisialisasi instance Font baru dengan nama keluarga font khusus, folder yang berisi font TrueType, ukuran, dan gaya. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Menginisialisasi instance Font baru dengan nama keluarga font khusus, folder yang berisi file font TrueType, dan ukuran. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Font tersebut tebal. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Nama keluarga Font ini. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | Folder yang berisi file font TrueType. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Fontnya miring. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | Ukuran Font ini. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Font menandakan garis horizontal melalui teks. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Informasi gaya untuk Font ini. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Font bergaris bawah. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Panduan tugas yang menggunakan `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
