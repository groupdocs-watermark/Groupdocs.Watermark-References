---
title: "méthode get_images"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Trouve les images selon les critères de recherche spécifiés."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Trouve les images selon les critères de recherche spécifiés.

La recherche est effectuée dans les objets spécifiés dans [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

En savoir plus sur la recherche de filigranes https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Les critères de recherche à utiliser. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Exemple

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

Trouve toutes les images du document.

La recherche est effectuée dans les objets spécifiés dans [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

En savoir plus sur la recherche de filigranes sur https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Exemple

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

        # Chaque image raster intégrée dans le document
        for image in watermarker.get_images():
            # Ignorer les petites images telles que les icônes ou les puces
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
