---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट इमेज डेटा का उपयोग करके DiagramWatermarkableImage क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

निर्दिष्ट इमेज डेटा का उपयोग करके [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) क्लास का नया उदाहरण आरंभ करता है।

```python
def __init__(self, image_data):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| image_data | `list[int]` | उस unsigned बाइट्स की एरे जिससे `DiagramWatermarkableImage` बनाया जाता है। |

### उदाहरण

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### संबंधित देखें
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
