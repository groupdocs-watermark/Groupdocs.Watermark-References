---
title: "DiagramShapeWatermarkOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Visio दस्तावेज़ में आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
is_root: false
weight: 50
---


## DiagramShapeWatermarkOptions class

Visio दस्तावेज़ में आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।

- Add watermarks to diagram documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

DiagramShapeWatermarkOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/__init__/) | [`DiagramShapeWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/) क्लास का नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [placement_type](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placement_type/) | वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए, यह निर्दिष्ट करने वाला मान। |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | यह प्रॉपर्टी दर्शाती है कि Visio में आकार का संपादन प्रतिबंधित है या नहीं। ([`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/) से विरासत में मिला है) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.diagram import DiagramShapeWatermarkOptions
from groupdocs.watermark.contents.diagram import DiagramWatermarkPlacementType

def add_watermark_to_diagram():
    with Watermarker("./diagram.vsdx") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = DiagramShapeWatermarkOptions()
        options.placement_type = DiagramWatermarkPlacementType.BACKGROUND_PAGES
        watermarker.add(watermark, options)

        watermarker.save("./output.vsdx")
```

### संबंधित देखें
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
