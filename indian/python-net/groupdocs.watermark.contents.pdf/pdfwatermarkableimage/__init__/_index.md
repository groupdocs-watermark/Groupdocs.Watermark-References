---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट छवि डेटा का उपयोग करके PdfWatermarkableImage क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

निम्नलिखित छवि डेटा का उपयोग करके [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) क्लास का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, image_data):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| image_data | `list[int]` | `PdfWatermarkableImage` बनाने के लिए अनसाइन्ड बाइट्स की एरे। |

### उदाहरण

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### संबंधित देखें
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
