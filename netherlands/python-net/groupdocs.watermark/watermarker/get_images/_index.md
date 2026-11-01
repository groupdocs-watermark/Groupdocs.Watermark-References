---
title: "get_images-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Vindt afbeeldingen volgens de opgegeven zoekcriteria."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Vindt afbeeldingen volgens de opgegeven zoekcriteria.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Meer informatie over het zoeken naar watermerken https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | De zoekcriteria om te gebruiken. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Voorbeeld

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

Vindt alle afbeeldingen in het document.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Meer informatie over het zoeken naar watermerken op https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Voorbeeld

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

        # Elke rasterafbeelding die in het document is ingebed
        for image in watermarker.get_images():
            # Sla kleine afbeeldingen over, zoals pictogrammen of opsommingstekens
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
