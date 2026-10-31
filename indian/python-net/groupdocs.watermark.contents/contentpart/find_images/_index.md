---
title: "find_images मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन ऑब्जेक्ट्स में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं।

```python
def find_images(self, search_criteria):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | उपयोग करने के लिए खोज मानदंड। |

**Returns:** The collection of the found images.

### उदाहरण

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

सामग्री में सभी छवियों को खोजता है, उन ऑब्जेक्ट्स के भीतर खोजते हुए जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं।

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### उदाहरण

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

### संबंधित देखें
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
