---
title: "rasterize मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "सभी सामग्री पृष्ठों को छवियों में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

सभी सामग्री पृष्ठों को छवियों में परिवर्तित करता है।

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| horizontal_resolution | `int` | क्षैतिज छवि रिज़ॉल्यूशन। |
| vertical_resolution | `int` | ऊर्ध्वाधर छवि रिज़ॉल्यूशन। |
| image_format | `PdfImageConversionFormat` | छवि प्रारूप। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # एक वॉटरमार्क जोड़ें (वैकल्पिक)
        # watermarker.add(TextWatermark(\"CONFIDENTIAL\", Font(\"Arial\", 19.0)))

        # प्रत्येक पृष्ठ को 100x100 DPI पर PNG छवियों में रास्टराइज़ करें
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### संबंधित देखें
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
