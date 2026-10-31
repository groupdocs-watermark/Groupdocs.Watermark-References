---
title: "rasterize मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "पृष्ठ सामग्री को एक छवि में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

पृष्ठ सामग्री को एक छवि में परिवर्तित करता है।

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # पहले पृष्ठ को 100 DPI पर PNG छवि में रास्टराइज़ करें।
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### संबंधित देखें
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
