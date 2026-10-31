---
title: "add मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "लोड किए गए दस्तावेज़ में एक वॉटरमार्क जोड़ता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

लोड किए गए दस्तावेज़ में एक वॉटरमार्क जोड़ता है।

GroupDocs दस्तावेज़ीकरण में वॉटरमार्क जोड़ने के बारे में अधिक जानें।

```python
def add(self, watermark):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| watermark | `Watermark` | दस्तावेज़ में जोड़ने के लिए वॉटरमार्क। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

वॉटरमार्क विकल्पों का उपयोग करके लोड किए गए दस्तावेज़ में एक वॉटरमार्क जोड़ता है।

वॉटरमार्क जोड़ने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| watermark | `Watermark` | दस्तावेज़ में जोड़ने के लिए वॉटरमार्क। |
| options | `WatermarkOptions` | वॉटरमार्क जोड़ते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

**Returns:** None.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
