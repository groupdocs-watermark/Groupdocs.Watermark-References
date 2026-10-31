---
title: "PdfLoadOptions वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "PDF दस्तावेज़ के लिए दस्तावेज़ लोड करने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/
is_root: false
weight: 30
---


## PdfLoadOptions class

PDF दस्तावेज़ के लिए दस्तावेज़ लोड करने के विकल्पों का प्रतिनिधित्व करता है।

PdfLoadOptions प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/) | [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) वर्ग का नया उदाहरण आरंभ करता है। |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/#password) | [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) वर्ग का नया उदाहरण निर्दिष्ट पासवर्ड के साथ आरंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | फ़ाइल का प्रकार, जो उसके फ़ॉर्मेट को दर्शाता है (जैसे, docx, pdf, xlsx, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | दस्तावेज़ का फ़ॉर्मेट फ़ैमिली, जो उसके प्रकार को दर्शाता है (जैसे, Image, Pdf, Spreadsheet, आदि)। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड। ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/) से विरासत में मिला) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/default/) | क्लास के लिए डिफ़ॉल्ट मान प्राप्त करता है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    # वॉटरमार्कर पर संचालन करें
    pass
```

### संबंधित देखें
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
