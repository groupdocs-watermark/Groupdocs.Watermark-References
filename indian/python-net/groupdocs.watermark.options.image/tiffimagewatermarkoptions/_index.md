---
title: "TiffImageWatermarkOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "TIFF छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
is_root: false
weight: 100
---


## TiffImageWatermarkOptions class

TIFF छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

TiffImageWatermarkOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/) | एक नया उदाहरण प्रारंभ करता है [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) क्लास का। |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/#frame_index) | एक नया [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) उदाहरण प्रारंभ करता है निर्दिष्ट फ्रेम इंडेक्स के साथ। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स। ([`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) से विरासत में मिला) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.red
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER

    options = TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)

    watermarker.save("./output.tiff")
```

### संबंधित देखें
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
