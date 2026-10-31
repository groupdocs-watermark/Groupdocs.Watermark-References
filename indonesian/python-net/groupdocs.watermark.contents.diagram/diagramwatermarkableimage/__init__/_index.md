---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas DiagramWatermarkableImage menggunakan data gambar yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Menginisialisasi sebuah instance baru dari kelas [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) menggunakan data gambar yang ditentukan.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_data | `list[int]` | Array byte tak bertanda yang digunakan untuk membuat `DiagramWatermarkableImage`. |

### Contoh

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Lihat Juga
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
