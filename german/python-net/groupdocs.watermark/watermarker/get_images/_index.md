---
title: "get_images Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Findet Bilder gemäß den angegebenen Suchkriterien."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Findet Bilder gemäß den angegebenen Suchkriterien.

Die Suche wird in Objekten durchgeführt, die in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) angegeben sind.

Erfahren Sie mehr über das Suchen von Wasserzeichen https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Die zu verwendenden Suchkriterien. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Beispiel

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

Findet alle Bilder im Dokument.

Die Suche wird in Objekten durchgeführt, die in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) angegeben sind.

Erfahren Sie mehr über das Suchen von Wasserzeichen unter https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Beispiel

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

        # Jedes Rasterbild, das im Dokument eingebettet ist
        for image in watermarker.get_images():
            # Kleine Bilder wie Symbole oder Aufzählungszeichen überspringen
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
