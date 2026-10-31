---
title: "find_images Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Findet Bilder gemäß den angegebenen Suchkriterien."
type: docs
url: /de/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) angegebenen Objekten durchgeführt.

```python
def find_images(self, search_criteria):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Die zu verwendenden Suchkriterien. |

**Returns:** The collection of the found images.

### Beispiel

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

Findet alle Bilder im Inhalt, indem in den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) angegebenen Objekten gesucht wird.

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### Beispiel

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

### Siehe auch
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
