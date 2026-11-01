---
title: "find_images metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hittar bilder enligt de angivna sökkriterierna."
type: docs
url: /sv/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self, search_criteria):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Sök kriterierna att använda. |

**Returns:** The collection of the found images.

### Exempel

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

Hittar alla bilder i innehållet och söker inom de objekt som anges i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### Exempel

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

### Se även
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
