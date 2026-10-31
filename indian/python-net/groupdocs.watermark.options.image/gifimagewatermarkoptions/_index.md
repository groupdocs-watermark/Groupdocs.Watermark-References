---
title: "GifImageWatermarkOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GIF छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
is_root: false
weight: 30
---


## GifImageWatermarkOptions class

GIF छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प दर्शाता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

GifImageWatermarkOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/) | [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/#frame_index) | [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) क्लास को निर्दिष्ट फ्रेम इंडेक्स के साथ एक नया उदाहरण प्रारंभ करता है। |

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
from groupdocs.watermark.options.image import GifImageLoadOptions, GifImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = GifImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))

    options = GifImageWatermarkOptions()
    options.frame_index = 0

    watermarker.add(watermark, options)
    watermarker.save()
```

### संबंधित देखें
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
