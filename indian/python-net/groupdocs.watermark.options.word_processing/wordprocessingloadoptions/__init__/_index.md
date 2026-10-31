---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "WordProcessingLoadOptions क्लास का नया उदाहरण आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#password}

निर्दिष्ट पासवर्ड के साथ WordProcessingLoadOptions क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, password):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| password | `str` | एन्क्रिप्टेड सामग्री खोलने के लिए पासवर्ड। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # वॉटरमार्क ऑपरेशन्स करें
    pass
```

### संबंधित देखें
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
