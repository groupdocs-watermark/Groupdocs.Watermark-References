---
title: "WordProcessingLoadOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Word दस्तावेज़ के लिए दस्तावेज़ लोडिंग विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Word दस्तावेज़ के लिए दस्तावेज़ लोडिंग विकल्पों का प्रतिनिधित्व करता है।

WordProcessingLoadOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | निर्दिष्ट पासवर्ड के साथ WordProcessingLoadOptions क्लास का एक नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | फ़ाइल का प्रकार, जो उसके फ़ॉर्मेट को दर्शाता है (जैसे, docx, pdf, xlsx, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | दस्तावेज़ का फ़ॉर्मेट फ़ैमिली, जो उसके प्रकार को दर्शाता है (जैसे, Image, Pdf, Spreadsheet, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # सामग्री पर संचालन करें, उदाहरण के लिए, संरक्षित करना, अनस्ट्रक्चर करना, वॉटरमार्क जोड़ना
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### संबंधित देखें
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
