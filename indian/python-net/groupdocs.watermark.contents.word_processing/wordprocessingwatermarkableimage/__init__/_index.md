---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट छवि डेटा का उपयोग करके WordProcessingWatermarkableImage क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

निर्दिष्ट छवि डेटा का उपयोग करके [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) क्लास की नई इंस्टेंस को प्रारंभ करता है।

```python
def __init__(self, image_data):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| image_data | `list[int]` | `WordProcessingWatermarkableImage` बनाने के लिए unsigned बाइट्स की array। |

### उदाहरण

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### संबंधित देखें
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
