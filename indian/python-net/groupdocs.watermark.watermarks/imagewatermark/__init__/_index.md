---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट फ़ाइल पथ के साथ नया ImageWatermark उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

निर्दिष्ट फ़ाइल पथ के साथ नया ImageWatermark उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | वॉटरमार्क के रूप में उपयोग की जाने वाली छवि का पथ। |

### उदाहरण

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

प्रदान किए गए इमेज स्ट्रीम के साथ नया ImageWatermark प्रारंभ करता है।

```python
def __init__(self, stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | वॉटरमार्क के रूप में उपयोग की जाने वाली छवि को शामिल करने वाला स्ट्रीम। |

### उदाहरण

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### संबंधित देखें
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
