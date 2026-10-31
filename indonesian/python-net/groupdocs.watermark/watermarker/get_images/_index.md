---
title: "metode get_images"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan.

Pencarian dilakukan pada objek yang ditentukan dalam [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Pelajari lebih lanjut tentang mencari watermark https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Kriteria pencarian yang akan digunakan. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType

with Watermarker("./document.pdf") as watermarker:
    watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
    watermark.foreground_color = Color.red
    watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS

    for image in watermarker.get_images():
        if image.width > 100 and image.height > 100:
            image.add(watermark)

    watermarker.save("./output.pdf")
```

## get_images

Menemukan semua gambar dalam dokumen.

Pencarian dilakukan pada objek yang ditentukan dalam [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Pelajari lebih lanjut tentang mencari watermark di https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # Setiap gambar raster yang disematkan dalam dokumen
        for image in watermarker.get_images():
            # Lewati gambar kecil seperti ikon atau bullet
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
