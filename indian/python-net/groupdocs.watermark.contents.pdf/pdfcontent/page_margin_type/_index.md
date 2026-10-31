---
title: "page_margin_type प्रॉपर्टी"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "वॉटरमार्क जोड़ते समय उपयोग किए जाने वाले pdf पेज मार्जिन।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

वॉटरमार्क जोड़ते समय उपयोग किए जाने वाले pdf पेज मार्जिन।

यह प्रॉपर्टी केवल तब काम करती है जब [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) को True पर सेट किया गया हो। यदि यह False हो, तो PDF CropBox को वॉटरमार्क क्षेत्र के रूप में उपयोग किया जाता है।

डिफ़ॉल्ट मान `PdfPageMarginType.trim_box` है।

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### संबंधित देखें
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
