---
title: "protect मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ को परिवर्तनों से सुरक्षित करता है और एक सुरक्षा पासवर्ड सेट करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

दस्तावेज़ को परिवर्तनों से सुरक्षित करता है और एक सुरक्षा पासवर्ड सेट करता है।

दस्तावेज़ की सामग्री को संपादन योग्य बनाने के लिए, `WordProcessingLockType.allow_only_form_fields` या `WordProcessingLockType.read_only_with_editable_content` पैरामीटर के साथ उपयुक्त वॉटरमार्क जोड़ने की विधि का उपयोग करें।

```python
def protect(self, protection_type, password):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | दस्तावेज़ के लिए सुरक्षा प्रकार निर्दिष्ट करता है। |
| password | `str` | दस्तावेज़ को सुरक्षित करने के लिए पासवर्ड। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### संबंधित देखें
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
