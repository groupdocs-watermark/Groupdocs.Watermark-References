---
title: "WordProcessingWatermarkSectionOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Word दस्तावेज़ सेक्शन में आकार वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/
is_root: false
weight: 120
---


## WordProcessingWatermarkSectionOptions class

Word दस्तावेज़ सेक्शन में आकार वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

और अधिक जानें:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

WordProcessingWatermarkSectionOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/__init__/) | एक नया उदाहरण प्रारंभ करता है [`WordProcessingWatermarkSectionOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/) क्लास। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [section_index](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/section_index/) | वॉटरमार्क जोड़ने के लिए सेक्शन का सूचकांक। |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | एक आकार के साथ जुड़ा वर्णनात्मक (वैकल्पिक) पाठ। ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) से विरासत में मिला है) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | वॉटरमार्क पर लागू करने के लिए प्रभाव, जो एक [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) या [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/) उदाहरण के रूप में निर्दिष्ट हैं। ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) से विरासत में मिला है) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | यह गुण दर्शाता है कि Word में आकार का संपादन प्रतिबंधित है या नहीं। ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) से विरासत में मिला है) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | वॉटरमार्क लॉक प्रकार। ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) से विरासत में मिला है) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | आकार का नाम। ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) से विरासत में मिला है) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | वॉटरमार्क को लॉक करने के लिए उपयोग किया गया पासवर्ड। ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) से विरासत में मिला है) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions,
)

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER
    watermark.foreground_color = Color.red

    options = WordProcessingWatermarkSectionOptions()
    options.section_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### संबंधित देखें
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
