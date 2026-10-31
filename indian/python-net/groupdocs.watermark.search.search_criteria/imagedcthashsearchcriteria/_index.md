---
title: "ImageDctHashSearchCriteria वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ में छवियों को खोजने के लिए खोज मानदंड दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

दस्तावेज़ में छवियों को खोजने के लिए खोज मानदंड दर्शाता है।

यह खोज मानदंड छवि समानता की गणना के लिए DCT आधारित परसेप्चुअल इमेज हैश का उपयोग करता है। अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

ImageDctHashSearchCriteria प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | निर्दिष्ट फ़ाइल पथ के साथ एक नया ImageDctHashSearchCriteria इंस्टेंस प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | प्रदान किए गए इमेज स्ट्रीम के साथ एक नया ImageDctHashSearchCriteria इंस्टेंस प्रारंभ करता है। |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | छवियों के बीच अधिकतम अनुमत अंतर। (से विरासत में मिला [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | विशिष्ट पृष्ठ संख्याओं की सूची। (से विरासत में मिला [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
`ImageDctHashSearchCriteria` का उपयोग करने वाले टास्क गाइड:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### संबंधित देखें
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
