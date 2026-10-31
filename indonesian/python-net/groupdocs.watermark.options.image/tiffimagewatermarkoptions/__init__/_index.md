---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru dari kelas TiffImageWatermarkOptions."
type: docs
url: /id/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari kelas [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

def add_watermark_to_image():
    with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = TiffImageWatermarkOptions()
        options.frame_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.tiff")
```

## __init__ {#frame_index}

Menginisialisasi sebuah instance baru [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) dengan indeks frame yang ditentukan.

```python
def __init__(self, frame_index):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| frame_index | `int` | Indeks frame untuk menambahkan watermark. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

def add_watermark_to_image():
    with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = TiffImageWatermarkOptions()
        options.frame_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.tiff")
```

### Lihat Juga
* class [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/)
