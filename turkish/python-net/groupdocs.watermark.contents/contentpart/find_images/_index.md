---
title: "find_images yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen arama kriterlerine göre görüntüleri bulur."
type: docs
url: /tr/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir.

```python
def find_images(self, search_criteria):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Kullanılacak arama kriteri. |

**Returns:** The collection of the found images.

### Örnek

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

İçerikteki tüm görüntüleri bulur, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesneler içinde arama yapar.

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### Örnek

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

### Ayrıca Bakınız
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
