---
title: "ColorRange क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "RGB रंग के HSB प्रतिनिधित्व का उपयोग करके रंगों की एक सीमा दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

RGB रंग के HSB प्रतिनिधित्व का उपयोग करके रंगों की एक सीमा दर्शाता है।

ColorRange प्रकार निम्नलिखित सदस्य उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) को निर्दिष्ट सटीक रंग के साथ नया इंस्टेंस इनिशियलाइज़ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | फ़्लैग जो दर्शाता है कि केवल खाली रंग रेंज में है या नहीं। |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | समाप्ति ब्राइटनेस मान, जो 0.0 (काला) से 1.0 (सफ़ेद) तक होता है। |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | समाप्ति ह्यू मान, डिग्री में। |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | समाप्ति सैचुरेशन मान। |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | प्रारंभिक ब्राइटनेस मान, जो 0.0 (काला) से 1.0 (सफ़ेद) तक होता है। |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | प्रारंभिक ह्यू मान, डिग्री में। |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | प्रारंभिक सैचुरेशन मान। |

### उदाहरण

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# फ़ोरग्राउंड रंग मिलान के लिए एक रंग रेंज बनाएं
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
`ColorRange` का उपयोग करने वाले टास्क गाइड्स:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### संबंधित देखें
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
