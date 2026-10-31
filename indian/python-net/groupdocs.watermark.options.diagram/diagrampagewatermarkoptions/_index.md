---
title: "DiagramPageWatermarkOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Visio दस्तावेज़ के किसी विशिष्ट पृष्ठ पर आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

Visio दस्तावेज़ के किसी विशिष्ट पृष्ठ पर आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

DiagramPageWatermarkOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | एक नया उदाहरण प्रारंभ करता है [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/) वर्ग का। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक। |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | यह प्रॉपर्टी दर्शाती है कि Visio में आकार का संपादन प्रतिबंधित है या नहीं। ([`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/) से विरासत में मिला है) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.diagram import DiagramPageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./diagram.vsdx") as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42.0))

    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.vsdx")
```

### संबंधित देखें
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
