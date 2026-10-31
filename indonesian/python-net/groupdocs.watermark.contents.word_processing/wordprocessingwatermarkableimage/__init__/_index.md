---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas WordProcessingWatermarkableImage menggunakan data gambar yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Menginisialisasi sebuah instance baru dari kelas [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) menggunakan data gambar yang ditentukan.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_data | `list[int]` | Array byte tak bertanda yang digunakan untuk membuat `WordProcessingWatermarkableImage`. |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Lihat Juga
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
