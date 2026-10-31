---
title: "DiagramLoadOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Visio दस्तावेज़ के लिए दस्तावेज़ लोडिंग विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Visio दस्तावेज़ के लिए दस्तावेज़ लोडिंग विकल्प दर्शाता है।

DiagramLoadOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) क्लास का नया उदाहरण प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) क्लास का नया उदाहरण निर्दिष्ट पासवर्ड के साथ प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | फ़ाइल का प्रकार, जो उसके फ़ॉर्मेट को दर्शाता है (जैसे, docx, pdf, xlsx, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | दस्तावेज़ का फ़ॉर्मेट फ़ैमिली, जो उसके प्रकार को दर्शाता है (जैसे, Image, Pdf, Spreadsheet, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। |

### उदाहरण

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    # यहाँ आकारों को संशोधित करें
    watermarker.save("output.vsdx")
```

### संबंधित देखें
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
