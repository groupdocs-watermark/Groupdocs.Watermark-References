---
title: "طريقة find_images"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يبحث عن الصور وفقًا لمعايير البحث المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self, search_criteria):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | معايير البحث التي سيتم استخدامها. |

**Returns:** The collection of the found images.

### مثال

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

يبحث عن جميع الصور في المحتوى، مع البحث داخل الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### مثال

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

### انظر أيضًا
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
