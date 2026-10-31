---
title: "méthode find_images"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Trouve les images selon les critères de recherche spécifiés."
type: docs
url: /fr/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Recherche des images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self, search_criteria):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Les critères de recherche à utiliser. |

**Returns:** The collection of the found images.

### Exemple

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

Recherche toutes les images dans le contenu, en recherchant parmi les objets spécifiés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### Exemple

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

### Voir aussi
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
