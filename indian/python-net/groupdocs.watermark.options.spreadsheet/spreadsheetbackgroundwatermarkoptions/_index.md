---
title: "SpreadsheetBackgroundWatermarkOptions वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "स्प्रेडशीट वर्कशीट में वॉटरमार्क को पृष्ठभूमि के रूप में जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

स्प्रेडशीट वर्कशीट में वॉटरमार्क को पृष्ठभूमि के रूप में जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

यह SpreadsheetBackgroundWatermarkOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/) वर्ग का एक नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में। |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में। |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | वॉटरमार्क जोड़ने के लिए कार्यपत्रक का इंडेक्स। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetBackgroundWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker(r"C:\Documents\test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36))

    options = SpreadsheetBackgroundWatermarkOptions()
    options.worksheet_index = -1  # default
    options.background_width = 800
    options.background_height = 600

    watermarker.add(watermark, options)
    watermarker.save()
```

### संबंधित देखें
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
