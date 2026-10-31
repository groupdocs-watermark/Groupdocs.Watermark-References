---
title: "SpreadsheetLoadOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "स्प्रेडशीट दस्तावेज़ के लिए दस्तावेज़ लोडिंग विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

स्प्रेडशीट दस्तावेज़ के लिए दस्तावेज़ लोडिंग विकल्पों का प्रतिनिधित्व करता है।

SpreadsheetLoadOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | नया उदाहरण प्रारंभ करता है [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) क्लास का। |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | निर्दिष्ट पासवर्ड के साथ नया उदाहरण प्रारंभ करता है [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) क्लास का। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | फ़ाइल का प्रकार, जो उसके फ़ॉर्मेट को दर्शाता है (जैसे, docx, pdf, xlsx, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | दस्तावेज़ का फ़ॉर्मेट फ़ैमिली, जो उसके प्रकार को दर्शाता है (जैसे, Image, Pdf, Spreadsheet, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # यहाँ वॉटरमार्क ऑपरेशन्स करें
    pass
```

### संबंधित देखें
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
