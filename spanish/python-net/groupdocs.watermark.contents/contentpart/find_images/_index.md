---
title: "método find_images"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Encuentra imágenes según los criterios de búsqueda especificados."
type: docs
url: /es/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se lleva a cabo en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self, search_criteria):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Los criterios de búsqueda a usar. |

**Returns:** The collection of the found images.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected image", Font("Arial", 8.0))
    content = watermarker.get_content()
    for image in content.sections[0].find_images():
        image.add(watermark)
    watermarker.save("./output.docx")
```

## find_images

Encuentra todas las imágenes en el contenido, buscando dentro de los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected image", Font("Arial", 8.0))
    content = watermarker.get_content()
    for image in content.sections[0].find_images():
        image.add(watermark)
    watermarker.save("./output.docx")
```

### Ver también
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
