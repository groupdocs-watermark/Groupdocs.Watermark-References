---
title: "WordProcessingContent क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक Word दस्तावेज़ (doc, docx, आदि) को दर्शाता है जहाँ वॉटरमार्क रखा जा सकता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

एक Word दस्तावेज़ (doc, docx, आदि) को दर्शाता है जहाँ वॉटरमार्क रखा जा सकता है।

और अधिक जानें:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

WordProcessingContent प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | दस्तावेज़ को डिक्रिप्ट करता है। |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | दस्तावेज़ को एन्क्रिप्ट करता है। |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | दस्तावेज़ को परिवर्तनों से सुरक्षित करता है और एक सुरक्षा पासवर्ड सेट करता है। |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | पासवर्ड की परवाह किए बिना दस्तावेज़ से सुरक्षा हटाता है। |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | वर्तमान इंस्टेंस को डिस्पोज़ करता है। ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) से विरासत में मिला) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन वस्तुओं में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क को खोजता है। खोज उन वस्तुओं पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | दस्तावेज़ में पृष्ठों की संख्या। |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | इस [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/) के सभी अनुभागों का संग्रह। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # यदि आवश्यक हो तो यहाँ किसी विशेष या सभी अनुभागों में वॉटरमार्क जोड़ें।
    watermarker.save("output.docx")
```

### संबंधित देखें
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
