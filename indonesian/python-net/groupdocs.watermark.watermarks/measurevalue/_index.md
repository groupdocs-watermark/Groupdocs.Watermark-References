---
title: "Kelas MeasureValue"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili nilai pengukuran dengan tipe tertentu dan nilai numerik."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Mewakili nilai pengukuran dengan tipe tertentu dan nilai numerik.

Tipe MeasureValue menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Jenis pengukuran. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Nilai numerik pengukuran; harus lebih besar dari 0. |

### Contoh

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Buat pengukuran yang dinyatakan sebagai persentase halaman
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
Panduan tugas yang menggunakan `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Lihat Juga
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
