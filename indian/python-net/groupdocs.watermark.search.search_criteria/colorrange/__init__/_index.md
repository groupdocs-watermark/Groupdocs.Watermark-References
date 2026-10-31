---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "ColorRange क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

[`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# डिफ़ॉल्ट कलर रेंज बनाएं
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

[`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) को निर्दिष्ट सटीक रंग के साथ नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, exact_color):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| exact_color | `Color` | वह सटीक रंग जिससे रेंज बनाई जाती है। |

### संबंधित देखें
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
