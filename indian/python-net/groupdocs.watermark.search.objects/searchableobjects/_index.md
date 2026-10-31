---
title: "SearchableObjects क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "वॉटरमार्क खोज में शामिल किए जाने वाले दस्तावेज़ ऑब्जेक्ट्स को निर्दिष्ट करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

वॉटरमार्क खोज में शामिल किए जाने वाले दस्तावेज़ ऑब्जेक्ट्स को निर्दिष्ट करता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SearchableObjects प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | एक नया उदाहरण प्रारंभ करता है [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) क्लास का। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Visio दस्तावेज़ के भीतर वे वस्तुएँ जो वॉटरमार्क खोज में शामिल की जानी हैं। |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | ईमेल संदेश के भीतर वे वस्तुएँ जो वॉटरमार्क खोज में शामिल की जानी हैं। |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | PDF दस्तावेज़ के भीतर वे वस्तुएँ जो वॉटरमार्क खोज में शामिल की जानी हैं। |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | PowerPoint दस्तावेज़ के भीतर वे वस्तुएँ जो वॉटरमार्क खोज में शामिल की जानी हैं। |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Excel दस्तावेज़ के भीतर वे वस्तुएँ जो वॉटरमार्क खोज में शामिल की जानी हैं। |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Word दस्तावेज़ के भीतर वे वस्तुएँ जो वॉटरमार्क खोज में शामिल की जानी हैं। |

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
`SearchableObjects` का उपयोग करने वाले कार्य मार्गदर्शक:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### संबंधित देखें
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
