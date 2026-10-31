---
title: "PreviewOptions क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "प्रीव्यू जनरेशन के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

प्रीव्यू जनरेशन के लिए आवश्यकताओं और स्ट्रीम डेलीगेट्स सेट करने के विकल्प प्रदान करता है।

PreviewOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | एक नया PreviewOptions इंस्टेंस प्रारंभ करता है जो उपयोग के बाद आउटपुट स्ट्रीम को बंद कर देता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | एक नया PreviewOptions इंस्टेंस प्रारंभ करता है जो क्लाइंट को आगे उपयोग के लिए आउटपुट स्ट्रीम लौटाता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | प्रत्येक रेंडर किए गए पृष्ठ के लिए लिखने योग्य स्ट्रीम प्राप्त करने हेतु उपयोग किया जाने वाला पृष्ठ स्ट्रीम निर्माण डेलीगेट। |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | पृष्ठ प्रीव्यू की ऊँचाई। |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | प्रीव्यू उत्पन्न करने के लिए पृष्ठ संख्याओं का एरे। |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | प्रीव्यू छवि प्रारूप। |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | पृष्ठ प्रीव्यू पूर्णता डेलीगेट। |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | पृष्ठ प्रीव्यू की चौड़ाई। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # प्रत्येक पृष्ठ को रेंडर करने के लिए एक लिखने योग्य फ़ाइल स्ट्रीम प्रदान करें
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
`PreviewOptions` का उपयोग करने वाले टास्क गाइड:

* [Document preview](/watermark/python-net/guides/preview/)

### संबंधित देखें
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
