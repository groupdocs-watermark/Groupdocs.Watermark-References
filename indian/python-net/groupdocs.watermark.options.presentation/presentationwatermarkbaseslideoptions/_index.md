---
title: "PresentationWatermarkBaseSlideOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "प्रेजेंटेशन दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

प्रेजेंटेशन दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।

और अधिक जानें:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

PresentationWatermarkBaseSlideOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | एक आकार के साथ जुड़ा वर्णनात्मक (वैकल्पिक) पाठ। |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | वॉटरमार्क पर लागू करने के लिए प्रभाव, जो एक [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) या एक [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) उदाहरण के रूप में निर्दिष्ट किए गए हैं। |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | यह प्रॉपर्टी दर्शाती है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं। |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | आकार का नाम। |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | वह प्रॉपर्टी जो दर्शाती है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### संबंधित देखें
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
