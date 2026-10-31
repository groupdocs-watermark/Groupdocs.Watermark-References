---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas SpreadsheetWatermarkableImage menggunakan data gambar yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Menginisialisasi instance baru dari kelas [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) menggunakan data gambar yang ditentukan.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_data | `list[int]` | Array byte tak bertanda yang digunakan untuk membuat `SpreadsheetWatermarkableImage`. |

### Contoh

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Lihat Juga
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
