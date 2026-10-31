---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट फ़ॉन्ट परिवार नाम और आकार के साथ एक नया Font उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

निर्दिष्ट फ़ॉन्ट परिवार नाम और आकार के साथ एक नया Font उदाहरण प्रारंभ करता है।

```python
def __init__(self, font_family_name, size):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| font_family_name | `str` | फ़ॉन्ट फ़ैमिली नाम। |
| size | `float` | नए फ़ॉन्ट का आकार। |

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

## __init__ {#font_family_name-size-style}

निर्दिष्ट फ़ॉन्ट परिवार नाम, आकार और शैली के साथ एक नया Font उदाहरण प्रारंभ करता है।

```python
def __init__(self, font_family_name, size, style):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| font_family_name | `str` | फ़ॉन्ट फ़ैमिली नाम। |
| size | `float` | नए फ़ॉन्ट का आकार। |
| style | `FontStyle` | नए फ़ॉन्ट की शैली। |

### उदाहरण

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

एक कस्टम फ़ॉन्ट परिवार नाम, TrueType फ़ॉन्ट्स वाले फ़ोल्डर, आकार और शैली के साथ एक नया Font उदाहरण प्रारंभ करता है।

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| font_family_name | `str` | फ़ॉन्ट फ़ैमिली नाम। |
| folder_path | `str` | फ़ोल्डर पथ जिसमें TrueType फ़ॉन्ट फ़ाइलें हैं। |
| size | `float` | नए फ़ॉन्ट का आकार। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

fonts_folder = r"c:\CustomFonts"
with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark(
        "Test watermark",
        Font("CustomFontName", fonts_folder, 36.0)
    )
    watermark.foreground_color = Color.blue
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("./output.pdf")
```

## __init__ {#font_family_name-folder_path-size-style}

एक कस्टम फ़ॉन्ट परिवार नाम, TrueType फ़ॉन्ट फ़ाइलों वाले फ़ोल्डर, और आकार के साथ एक नया Font उदाहरण प्रारंभ करता है।

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| font_family_name | `str` | फ़ॉन्ट फ़ैमिली नाम। |
| folder_path | `str` | फ़ोल्डर पथ जिसमें TrueType फ़ॉन्ट फ़ाइलें हैं। |
| size | `float` | नए फ़ॉन्ट का आकार। |
| style | `FontStyle` |  |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark(
        "Test watermark",
        Font("CustomFontName", r"c:\CustomFonts", 36.0)
    )
    watermark.foreground_color = Color.blue
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("./output.pdf")
```

### संबंधित देखें
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
