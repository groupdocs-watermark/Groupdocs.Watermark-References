---
title: "SpreadsheetWatermarkHeaderFooterOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "स्प्रेडशीट हेडर/फ़ूटर में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

स्प्रेडशीट हेडर/फ़ूटर में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

SpreadsheetWatermarkHeaderFooterOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | नया उदाहरण प्रारंभ करता है [`SpreadsheetWatermarkHeaderFooterOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/) क्लास का। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | वॉटरमार्क जोड़ने के लिए कार्यपत्रक का सूचकांक। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkHeaderFooterOptions
from groupdocs.watermark.watermarks import Font, TextWatermark
load_options = SpreadsheetLoadOptions()
with Watermarker("./test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 14))
    options = SpreadsheetWatermarkHeaderFooterOptions()
    options.worksheet_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### संबंधित देखें
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
