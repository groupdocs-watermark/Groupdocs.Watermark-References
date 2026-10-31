---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance ImageWatermark baru dengan jalur file yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Menginisialisasi instance ImageWatermark baru dengan jalur file yang ditentukan.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur ke gambar yang akan digunakan sebagai watermark. |

### Contoh

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Menginisialisasi ImageWatermark baru dengan aliran gambar yang disediakan.

```python
def __init__(self, stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran yang berisi gambar yang akan digunakan sebagai watermark. |

### Contoh

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### Lihat Juga
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
