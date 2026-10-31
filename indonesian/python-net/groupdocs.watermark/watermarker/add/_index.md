---
title: "metode add"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menambahkan watermark ke dokumen yang dimuat menggunakan opsi watermark."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Menambahkan watermark ke dokumen yang dimuat menggunakan opsi watermark.

Pelajari lebih lanjut tentang menambahkan watermark di dokumentasi GroupDocs.

```python
def add(self, watermark):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| watermark | `Watermark` | Watermark yang akan ditambahkan ke dokumen. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

Menghasilkan gambar pratinjau untuk dokumen.

Pelajari lebih lanjut tentang menambahkan watermark: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| watermark | `Watermark` | Watermark yang akan ditambahkan ke dokumen. |
| options | `WatermarkOptions` | Opsi tambahan untuk digunakan saat menambahkan watermark. |

**Returns:** None.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
