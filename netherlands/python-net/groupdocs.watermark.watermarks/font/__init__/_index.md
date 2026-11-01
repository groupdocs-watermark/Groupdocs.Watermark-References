---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw Font‑exemplaar met de opgegeven lettertypefamilienaam en grootte."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Initialiseert een nieuw Font‑exemplaar met de opgegeven lettertypefamilienaam en grootte.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_family_name | `str` | De naam van de lettertypefamilie. |
| size | `float` | De grootte van het nieuwe lettertype. |

### Voorbeeld

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

Initialiseert een nieuw Font‑exemplaar met de opgegeven lettertypefamilienaam, grootte en stijl.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_family_name | `str` | De naam van de lettertypefamilie. |
| size | `float` | De grootte van het nieuwe lettertype. |
| style | `FontStyle` | De stijl van het nieuwe lettertype. |

### Voorbeeld

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Initialiseert een nieuw Font‑exemplaar met een aangepaste lettertypefamilienaam, een map met TrueType-lettertypen, een grootte en een stijl.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_family_name | `str` | De naam van de lettertypefamilie. |
| folder_path | `str` | Mappad dat TrueType-lettertypebestanden bevat. |
| size | `float` | De grootte van het nieuwe lettertype. |

### Voorbeeld

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

Initialiseert een nieuw Font‑exemplaar met een aangepaste lettertypefamilienaam, de map met de TrueType-lettertypebestanden, en een grootte.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_family_name | `str` | De naam van de lettertypefamilie. |
| folder_path | `str` | Mappad dat TrueType-lettertypebestanden bevat. |
| size | `float` | De grootte van het nieuwe lettertype. |
| style | `FontStyle` |  |

### Voorbeeld

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

### Zie ook
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
