---
title: "get_images yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen arama kriterlerine göre görüntüleri bulur."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Belirtilen arama kriterlerine göre görüntüleri bulur.

Arama, [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) içinde belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Kullanılacak arama kriteri. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Örnek

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

Belgedeki tüm görüntüleri bulur.

Arama, [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) içinde belirtilen nesnelerde gerçekleştirilir.

https://docs.groupdocs.com/display/watermarknet/Searching+watermarks adresinde filigran arama hakkında daha fazla bilgi edinin.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Örnek

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

        # Belgeye gömülü her raster görüntü
        for image in watermarker.get_images():
            # Simge veya madde işaretleri gibi küçük görüntüleri atlayın
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
