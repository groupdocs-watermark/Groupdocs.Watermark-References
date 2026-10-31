---
title: "MeasureValue क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "विशिष्ट प्रकार और संख्यात्मक मान के साथ माप मान का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

विशिष्ट प्रकार और संख्यात्मक मान के साथ माप मान का प्रतिनिधित्व करता है।

MeasureValue प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | माप का प्रकार। |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | माप का संख्यात्मक मान; यह 0 से बड़ा होना चाहिए। |

### उदाहरण

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# पृष्ठ के प्रतिशत के रूप में व्यक्त एक माप बनाएं
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
`MeasureValue` का उपयोग करने वाले टास्क गाइड्स:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### संबंधित देखें
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
