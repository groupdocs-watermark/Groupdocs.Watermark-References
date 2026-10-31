---
title: "metodo get_images"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Trova le immagini secondo i criteri di ricerca specificati."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Trova le immagini secondo i criteri di ricerca specificati.

La ricerca viene eseguita negli oggetti specificati in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Maggiori informazioni sulla ricerca di filigrane https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | I criteri di ricerca da utilizzare. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Esempio

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

Trova tutte le immagini nel documento.

La ricerca viene eseguita negli oggetti specificati in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Maggiori informazioni sulla ricerca di filigrane su https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Esempio

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

        # Ogni immagine raster incorporata nel documento
        for image in watermarker.get_images():
            # Ignora le piccole immagini come icone o pallini
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
