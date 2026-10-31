---
title: "TextFormattingSearchCriteria वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "टेक्स्ट फ़ॉर्मेटिंग द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

टेक्स्ट फ़ॉर्मेटिंग द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

और अधिक जानें:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

TextFormattingSearchCriteria प्रकार निम्नलिखित सदस्यों को प्रदर्शित करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | एक नया उदाहरण प्रारंभ करता है [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/). |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | तार्किक AND ऑपरेटर का उपयोग करके इस SearchCriteria को अन्य मानदंडों के साथ संयोजित करता है। (से विरासत में मिला [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (से विरासत में मिला [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | इस SearchCriteria को नकारता है। (से विरासत में मिला [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | तार्किक OR ऑपरेटर का उपयोग करके इस SearchCriteria को अन्य मानदंडों के साथ संयोजित करता है। (से विरासत में मिला [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (से विरासत में मिला [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | रंगों की वह सीमा जो पाठ पृष्ठभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग की जाती है। |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | वॉटरमार्क टेक्स्ट फ़ॉर्मेटिंग में उपयोग किया गया फ़ॉन्ट बोल्ड है। |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | font_italic प्रॉपर्टी दर्शाती है कि वॉटरमार्क टेक्स्ट फ़ॉन्ट इटैलिक है या नहीं। |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | संभव वॉटरमार्क टेक्स्ट फ़ॉर्मेटिंग में उपयोग किए गए फ़ॉन्ट का नाम। |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | वॉटरमार्क टेक्स्ट फ़ॉर्मेटिंग के लिए फ़ॉन्ट स्ट्राइकआउट फ़्लैग। |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | फ़ॉन्ट अंडरलाइन फ़्लैग जो दर्शाता है कि वॉटरमार्क टेक्स्ट अंडरलाइन उपयोग करता है या नहीं। |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | टेक्स्ट फ़ोरग्राउंड रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की रेंज। |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | फ़ॉन्ट आकार का समाप्ति मान। |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | फ़ॉन्ट आकार का प्रारंभिक मान। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```

### Guides
`TextFormattingSearchCriteria` का उपयोग करने वाले टास्क गाइड्स:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### संबंधित देखें
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
