---
title: "metodo find_images"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Trova le immagini in base ai criteri di ricerca specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Trova le immagini secondo i criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self, search_criteria):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | I criteri di ricerca da utilizzare. |

**Returns:** The collection of the found images.

### Esempio

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

Trova tutte le immagini nel contenuto, cercando tra gli oggetti specificati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### Esempio

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

### Vedi anche
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
