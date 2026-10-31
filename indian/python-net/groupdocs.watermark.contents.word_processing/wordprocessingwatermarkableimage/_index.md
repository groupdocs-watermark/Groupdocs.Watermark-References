---
title: "WordProcessingWatermarkableImage क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Word दस्तावेज़ के अंदर एक इमेज को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/
is_root: false
weight: 190
---


## WordProcessingWatermarkableImage class

Word दस्तावेज़ के अंदर एक इमेज को दर्शाता है।

यह WordProcessingWatermarkableImage प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/#image_data) | निर्दिष्ट छवि डेटा का उपयोग करके [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) क्लास की नई इंस्टेंस को प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | इस [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) में वॉटरमार्क जोड़ता है। यह विधि मानती है कि वॉटरमार्क ऑफ़सेट और आकार पिक्सेल में मापे गए हैं (यदि उन्हें असाइन किया गया है)। (विरासत में मिला [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (विरासत में मिला [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन वस्तुओं में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | छवि को बाइट एरे के रूप में प्राप्त करता है। (विरासत में मिला [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क को खोजता है। खोज उन वस्तुओं पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | इस [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) की ऊँचाई पिक्सेल में। (विरासत में मिला [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | इस WatermarkableImage की चौड़ाई पिक्सेल में। (विरासत में मिला [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### उदाहरण

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()
image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### संबंधित देखें
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
