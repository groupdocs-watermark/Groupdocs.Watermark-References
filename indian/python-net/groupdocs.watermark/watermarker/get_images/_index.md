---
title: "get_images मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है।

खोज उन वस्तुओं में की जाती है जो [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) में निर्दिष्ट हैं।

वॉटरमार्क खोजने के बारे में अधिक जानें https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | उपयोग करने के लिए खोज मानदंड। |

**Returns:** WatermarkableImageCollection: The collection of found images.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType

with Watermarker("./document.pdf") as watermarker:
    watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
    watermark.foreground_color = Color.red
    watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS

    for image in watermarker.get_images():
        if image.width > 100 and image.height > 100:
            image.add(watermark)

    watermarker.save("./output.pdf")
```

## get_images

दस्तावेज़ में सभी छवियों को खोजता है।

खोज उन वस्तुओं में की जाती है जो [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) में निर्दिष्ट हैं।

वॉटरमार्क खोजने के बारे में अधिक जानें https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # दस्तावेज़ में एम्बेड किया गया प्रत्येक रास्टर इमेज
        for image in watermarker.get_images():
            # आइकन या बुलेट जैसे छोटे इमेज को छोड़ें
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
