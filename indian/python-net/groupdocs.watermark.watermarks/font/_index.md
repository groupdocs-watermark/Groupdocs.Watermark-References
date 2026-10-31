---
title: "Font वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक फ़ॉन्ट का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

एक फ़ॉन्ट का प्रतिनिधित्व करता है।

Font प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | निर्दिष्ट फ़ॉन्ट परिवार नाम और आकार के साथ एक नया Font उदाहरण प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | निर्दिष्ट फ़ॉन्ट परिवार नाम, आकार और शैली के साथ एक नया Font उदाहरण प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | एक कस्टम फ़ॉन्ट परिवार नाम, TrueType फ़ॉन्ट्स वाले फ़ोल्डर, आकार और शैली के साथ एक नया Font उदाहरण प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | एक कस्टम फ़ॉन्ट परिवार नाम, TrueType फ़ॉन्ट फ़ाइलों वाले फ़ोल्डर, और आकार के साथ एक नया Font उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | फ़ॉन्ट बोल्ड है। |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | इस Font का परिवार नाम। |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | फ़ोल्डर जिसमें TrueType फ़ॉन्ट फ़ाइलें हैं। |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | फ़ॉन्ट इटैलिक है। |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | इस फ़ॉन्ट का आकार। |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | फ़ॉन्ट टेक्स्ट के माध्यम से एक क्षैतिज रेखा निर्दिष्ट करता है। |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | इस फ़ॉन्ट के लिए शैली जानकारी। |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | फ़ॉन्ट रेखांकित है। |

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

### Guides
`Font` का उपयोग करने वाले टास्क गाइड:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### संबंधित देखें
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
