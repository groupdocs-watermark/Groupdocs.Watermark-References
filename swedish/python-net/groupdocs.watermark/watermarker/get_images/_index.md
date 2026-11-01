---
title: "get_images‑metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hittar bilder enligt angivna sökkriterier."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Hittar bilder enligt angivna sökkriterier.

Sökningen utförs i objekt som anges i [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Läs mer om att söka efter vattenstämplar https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Sök kriterierna att använda. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Exempel

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

Hittar alla bilder i dokumentet.

Sökningen utförs i objekt som anges i [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Läs mer om att söka efter vattenstämplar på https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Exempel

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

        # Varje rasterbild som är inbäddad i dokumentet
        for image in watermarker.get_images():
            # Hoppa över små bilder som ikoner eller punkter
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
