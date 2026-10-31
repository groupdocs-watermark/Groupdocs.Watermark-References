---
title: "WatermarkerSettings क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Watermarker व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Watermarker व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।

WatermarkerSettings प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | WatermarkerSettings का एक नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | वॉटरमार्किंग के दौरान घटनाओं और त्रुटियों को लॉग करने के लिए उपयोग किया जाने वाला लॉगर। |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | वॉटरमार्क खोज में शामिल किए जाने वाले खोज योग्य वस्तुएँ। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
`WatermarkerSettings` का उपयोग करने वाले टास्क गाइड:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### संबंधित देखें
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
