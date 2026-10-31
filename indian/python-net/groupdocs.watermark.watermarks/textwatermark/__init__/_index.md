---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट पाठ और फ़ॉन्ट के साथ एक नया TextWatermark बनाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

निर्दिष्ट पाठ और फ़ॉन्ट के साथ एक नया TextWatermark बनाता है।

```python
def __init__(self, text, font):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| text | `str` | वॉटरमार्क के रूप में उपयोग किया जाने वाला पाठ। |
| font | `Font` | टेक्स्ट का फ़ॉन्ट। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### संबंधित देखें
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
