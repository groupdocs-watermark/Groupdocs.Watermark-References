---
title: "create_page_stream प्रॉपर्टी"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "प्रत्येक रेंडर किए गए पृष्ठ के लिए लिखने योग्य स्ट्रीम प्राप्त करने हेतु उपयोग किया जाने वाला पृष्ठ स्ट्रीम निर्माण डेलीगेट।"
type: docs
url: /hi/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

प्रत्येक रेंडर किए गए पृष्ठ के लिए लिखने योग्य स्ट्रीम प्राप्त करने हेतु उपयोग किया जाने वाला पृष्ठ स्ट्रीम निर्माण डेलीगेट।

GroupDocs.Watermark दस्तावेज़ पृष्ठों को छवियों के रूप में रेंडर करता है। एक callable प्रदान करें जो पृष्ठ संख्या (`int`) प्राप्त करता है और एक लिखने योग्य `io.RawIOBase` स्ट्रीम लौटाता है; लाइब्रेरी रेंडर की गई छवि को स्ट्रीम में लिखती है और उसे बंद कर देती है।

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### संबंधित देखें
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
