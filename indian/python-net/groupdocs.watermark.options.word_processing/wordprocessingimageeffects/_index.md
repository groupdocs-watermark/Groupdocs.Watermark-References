---
title: "WordProcessingImageEffects क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Word दस्तावेज़ के लिए छवि वॉटरमार्क पर लागू किए जा सकने वाले प्रभावों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Word दस्तावेज़ के लिए छवि वॉटरमार्क पर लागू किए जा सकने वाले प्रभावों का प्रतिनिधित्व करता है।

WordProcessingImageEffects प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) क्लास का एक नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | छवि सीमा के लिए लाइन फ़ॉर्मेट सेटिंग्स। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | चित्र की चमक। यह 0.0 (सबसे धुंधला) और 1.0 (सबसे उज्ज्वल) के बीच एक फ्लोट होना चाहिए। डिफ़ॉल्ट मान 0.5 है। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | छवि का वह रंग मान जो पारदर्शी माना जाएगा। डिफ़ॉल्ट मान पूरी तरह पारदर्शी रंग है। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | निर्दिष्ट चित्र के लिए कंट्रास्ट। यह 0.0 (सबसे कम कंट्रास्ट) और 1.0 (सबसे अधिक कंट्रास्ट) के बीच एक फ्लोट होना चाहिए। डिफ़ॉल्ट मान 0.5 है। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | यह गुण दर्शाता है कि चित्र ग्रेस्केल मोड में प्रदर्शित होगा या नहीं। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

### संबंधित देखें
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
