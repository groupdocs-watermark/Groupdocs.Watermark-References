---
title: "SpreadsheetContent क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक Excel दस्तावेज़ को दर्शाता है जहाँ वॉटरमार्क रखा जा सकता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

एक Excel दस्तावेज़ को दर्शाता है जहाँ वॉटरमार्क रखा जा सकता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

SpreadsheetContent प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | दस्तावेज़ को डिक्रिप्ट करता है। |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | सामग्री को एन्क्रिप्ट करता है। |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | वर्तमान इंस्टेंस को डिस्पोज़ करता है। ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) से विरासत में मिला) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन वस्तुओं में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क को खोजता है। खोज उन वस्तुओं पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | इस [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/) की सभी कार्यपत्रकों का संग्रह। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # किसी विशिष्ट या सभी कार्यपत्रकों में वॉटरमार्क जोड़ने के लिए add मेथड का उपयोग करें।
    watermarker.save(r"D:\output.xls")
```

### संबंधित देखें
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
