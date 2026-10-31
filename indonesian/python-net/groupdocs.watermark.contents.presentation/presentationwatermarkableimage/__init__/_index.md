---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru dari kelas PresentationWatermarkableImage menggunakan data gambar yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Menginisialisasi instance baru dari kelas [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) menggunakan data gambar yang ditentukan.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_data | `list[int]` | Array byte tak bertanda yang digunakan untuk membuat `PresentationWatermarkableImage`. |

### Contoh

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Lihat Juga
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
