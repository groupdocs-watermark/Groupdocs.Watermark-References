---
title: "VectorSearchCriteria वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "वॉटरमार्क रंग द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

वॉटरमार्क रंग द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

VectorSearchCriteria प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | एक नया [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/) उदाहरण प्रारंभ करता है। |

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
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | फ़ोरग्राउंड रंग द्वारा वेक्टर वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import VectorSearchCriteria, ColorRange
from groupdocs.watermark.watermarks import Color

with Watermarker("./document.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = Color.from_argb(255, 169, 170, 174)  # #a9aaae
    color_range = ColorRange(watermark_color)
    color_range.min_brightness = 0.1
    color_range.max_brightness = 0.7
    search_criteria.vector_color_range = color_range

    possible_watermarks = watermarker.search(search_criteria)
    possible_watermarks.clear()
    watermarker.save("./output.pdf")
```

### संबंधित देखें
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
