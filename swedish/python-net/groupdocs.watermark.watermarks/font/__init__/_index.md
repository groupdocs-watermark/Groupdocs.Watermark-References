---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny Font-instans med det angivna teckensnittsfamiljenamnet och storleken."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Initierar en ny Font-instans med det angivna teckensnittsfamiljenamnet och storleken.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_family_name | `str` | Teckensnittsfamiljens namn. |
| size | `float` | Storleken på det nya teckensnittet. |

### Exempel

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

Initierar en ny Font-instans med det angivna teckensnittsfamiljenamnet, storleken och stilen.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_family_name | `str` | Teckensnittsfamiljens namn. |
| size | `float` | Storleken på det nya teckensnittet. |
| style | `FontStyle` | Stilen på det nya teckensnittet. |

### Exempel

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Initierar en ny Font-instans med ett anpassat teckensnittsfamiljenamn, en mapp som innehåller TrueType-teckensnitt, en storlek och en stil.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_family_name | `str` | Teckensnittsfamiljens namn. |
| folder_path | `str` | Mappväg som innehåller TrueType-teckensnittsfiler. |
| size | `float` | Storleken på det nya teckensnittet. |

### Exempel

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

Initierar en ny Font-instans med ett anpassat teckensnittsfamiljenamn, mappen som innehåller TrueType-teckensnittsfilerna och en storlek.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_family_name | `str` | Teckensnittsfamiljens namn. |
| folder_path | `str` | Mappväg som innehåller TrueType-teckensnittsfiler. |
| size | `float` | Storleken på det nya teckensnittet. |
| style | `FontStyle` |  |

### Exempel

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

### Se även
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
