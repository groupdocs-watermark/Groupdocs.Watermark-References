---
title: "get_images método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Encuentra imágenes según los criterios de búsqueda especificados."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Encuentra imágenes según los criterios de búsqueda especificados.

La búsqueda se realiza en los objetos especificados en [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Obtenga más información sobre la búsqueda de marcas de agua https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Los criterios de búsqueda a usar. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Ejemplo

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

Encuentra todas las imágenes en el documento.

La búsqueda se realiza en los objetos especificados en [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Obtenga más información sobre la búsqueda de marcas de agua en https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Ejemplo

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

        # Cada imagen raster incrustada en el documento
        for image in watermarker.get_images():
            # Omitir imágenes pequeñas como íconos o viñetas
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
