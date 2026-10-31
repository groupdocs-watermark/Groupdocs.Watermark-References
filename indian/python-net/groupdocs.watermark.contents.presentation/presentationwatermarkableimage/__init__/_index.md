---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट इमेज डेटा का उपयोग करके PresentationWatermarkableImage क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

निर्दिष्ट इमेज डेटा का उपयोग करके [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, image_data):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| image_data | `list[int]` | `PresentationWatermarkableImage` बनाने के लिए अनसाइन्ड बाइट्स की एरे। |

### उदाहरण

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### संबंधित देखें
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
