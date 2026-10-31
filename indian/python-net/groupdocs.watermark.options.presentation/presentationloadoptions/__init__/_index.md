---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "PresentationLoadOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) क्लास का नया उदाहरण आरंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

def remove_slide_background():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.slides[0].image_fill_format.background_image = None
        watermarker.save("./output.pptx")
```

## __init__ {#password}

निर्दिष्ट पासवर्ड के साथ PresentationLoadOptions क्लास का नया उदाहरण आरंभ करता है।

```python
def __init__(self, password):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| password | `str` | एन्क्रिप्टेड सामग्री खोलने के लिए पासवर्ड। |

### उदाहरण

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### संबंधित देखें
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
