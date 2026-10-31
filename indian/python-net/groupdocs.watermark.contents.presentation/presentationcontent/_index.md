---
title: "PresentationContent क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक PowerPoint दस्तावेज़ जहाँ वॉटरमार्क रखा जा सकता है, दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

एक PowerPoint दस्तावेज़ जहाँ वॉटरमार्क रखा जा सकता है, दर्शाता है।

और अधिक जानें:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

PresentationContent प्रकार निम्नलिखित सदस्य उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | दस्तावेज़ को डिक्रिप्ट करता है। |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | दस्तावेज़ को एन्क्रिप्ट करता है। |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | वर्तमान इंस्टेंस को डिस्पोज़ करता है। ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) से विरासत में मिला) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन वस्तुओं में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क को खोजता है। खोज उन वस्तुओं पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | इस [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) के सभी लेआउट स्लाइड्स का संग्रह। |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | इस [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) की मास्टर हैंडआउट स्लाइड। |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | इस [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) के सभी नोट्स स्लाइड्स के लिए मास्टर स्लाइड। |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | इस PresentationContent के सभी मास्टर स्लाइड्स का संग्रह। |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | नोट्स स्लाइड की ऊँचाई पॉइंट्स में। |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | नोट्स स्लाइड की चौड़ाई पॉइंट्स में। |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | स्लाइड की ऊँचाई पॉइंट्स में। |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | स्लाइड की चौड़ाई पॉइंट्स में। |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | इस [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) की सभी स्लाइड्स का संग्रह। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # किसी विशेष स्लाइड या सभी स्लाइड्स में वॉटरमार्क जोड़ने के लिए add मेथड का उपयोग करें।
    watermarker.save(r"D:\output.ppt")
```

### संबंधित देखें
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
