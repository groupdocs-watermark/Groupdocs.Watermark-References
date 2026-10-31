---
title: "Kelas TileOptions"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili opsi untuk mengonfigurasi watermark dalam mode ubin."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/tileoptions/
is_root: false
weight: 140
---


## TileOptions class

Mewakili opsi untuk mengonfigurasi watermark dalam mode ubin.

Tipe TileOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/__init__/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [line_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/line_spacing/) | Jarak antar baris untuk watermark dalam mode ubin. |
| [rotate_around_origin](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/rotate_around_origin/) | Properti ini menunjukkan apakah watermark yang diulang diputar di sekitar pusat dokumen. |
| [tile_type](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/tile_type/) | Jenis perataan ubin untuk watermark. |
| [watermark_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/watermark_spacing/) | Jarak antar seri untuk watermark dalam mode ubin. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.gray
    watermark.opacity = 0.3
    watermark.rotate_angle = -45.0
    watermark.text_alignment = TextAlignment.CENTER

    line_spacing = MeasureValue()
    line_spacing.measure_type = TileMeasureType.PERCENT
    line_spacing.value = 12.0

    watermark_spacing = MeasureValue()
    watermark_spacing.measure_type = TileMeasureType.PERCENT
    watermark_spacing.value = 10.0

    tile_options = TileOptions()
    tile_options.tile_type = TileType.ONE_THIRD_OFFSET
    tile_options.line_spacing = line_spacing
    tile_options.watermark_spacing = watermark_spacing
    watermark.tile_options = tile_options

    watermarker.add(watermark)
```

### Guides
Panduan tugas yang menggunakan `TileOptions`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
