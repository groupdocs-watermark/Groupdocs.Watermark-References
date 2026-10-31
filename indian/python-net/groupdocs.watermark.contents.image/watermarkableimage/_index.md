---
title: "WatermarkableImage वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ के भीतर एक छवि का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

दस्तावेज़ के भीतर एक छवि का प्रतिनिधित्व करता है।

और अधिक जानें:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

WatermarkableImage प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | इस [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) में वॉटरमार्क जोड़ता है। यह मेथड मानता है कि वॉटरमार्क ऑफ़सेट और आकार पिक्सेल में मापे गए हैं (यदि उन्हें असाइन किया गया हो)। |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | इमेज को बाइट ऐरे के रूप में प्राप्त करता है। |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन वस्तुओं में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क को खोजता है। खोज उन वस्तुओं पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | इस [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) की ऊँचाई पिक्सेल में। |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | इस WatermarkableImage की चौड़ाई पिक्सेल में। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # टेक्स्ट वॉटरमार्क को इनिशियलाइज़ करें।
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # दस्तावेज़ में सभी इमेज खोजें।
    images = watermarker.get_images()

    # प्रत्येक इमेज में वॉटरमार्क जोड़ें।
    for img in images:
        img.add(watermark)

    # परिवर्तनों को सहेजें।
    watermarker.save(r"D:\output.doc")
```

### संबंधित देखें
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
