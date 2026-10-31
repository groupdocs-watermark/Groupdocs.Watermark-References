---
title: "TextSearchCriteria वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "वॉटरमार्क टेक्स्ट द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

वॉटरमार्क टेक्स्ट द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

और अधिक जानें:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

TextSearchCriteria प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | निर्दिष्ट नियमित अभिव्यक्ति के साथ नया TextSearchCriteria प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | खोज स्ट्रिंग और केस‑सेंसिटिव तुलना के लिए फ़्लैग के साथ [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) वर्ग का एक नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | खोज स्ट्रिंग के साथ [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) वर्ग का एक नया इंस्टेंस प्रारंभ करता है। |

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
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | मैच करने के लिए नियमित अभिव्यक्ति पैटर्न। |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाता है या नहीं, यह दर्शाने वाली प्रॉपर्टी। |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | विशिष्ट पृष्ठ संख्याओं की सूची। (से विरासत में मिला [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Guides
`TextSearchCriteria` का उपयोग करने वाले टास्क गाइड:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### संबंधित देखें
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
