---
title: "IDocumentInfo वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "बुनियादी दस्तावेज़ जानकारी प्राप्त करने के लिए आवश्यक विधियों को प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

बुनियादी दस्तावेज़ जानकारी प्राप्त करने के लिए आवश्यक विधियों को प्रदान करता है।

और अधिक जानें: दस्तावेज़ जानकारी प्राप्त करें।

IDocumentInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | फ़ाइल फ़ॉर्मेट विवरण। |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | यह प्रॉपर्टी दर्शाती है कि दस्तावेज़ एन्क्रिप्टेड है और खोलने के लिए पासवर्ड आवश्यक है। |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | कुल पृष्ठ गणना। |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | दस्तावेज़ पृष्ठ विवरणों का संग्रह। |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | बाइट्स में दस्तावेज़ आकार। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### संबंधित देखें
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
