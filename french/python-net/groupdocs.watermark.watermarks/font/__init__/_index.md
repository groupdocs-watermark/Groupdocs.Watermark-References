---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de Font avec le nom de famille de police et la taille spécifiés."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Initialise une nouvelle instance de Font avec le nom de famille de police et la taille spécifiés.

```python
def __init__(self, font_family_name, size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | Le nom de la famille de police. |
| size | `float` | La taille de la nouvelle police. |

### Exemple

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

Initialise une nouvelle instance de Font avec le nom de famille de police, la taille et le style spécifiés.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | Le nom de la famille de police. |
| size | `float` | La taille de la nouvelle police. |
| style | `FontStyle` | Le style de la nouvelle police. |

### Exemple

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Initialise une nouvelle instance de Font avec un nom de famille de police personnalisé, un dossier contenant des polices TrueType, une taille et un style.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | Le nom de la famille de police. |
| folder_path | `str` | Chemin du dossier contenant les fichiers de police TrueType. |
| size | `float` | La taille de la nouvelle police. |

### Exemple

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

Initialise une nouvelle instance de Font avec un nom de famille de police personnalisé, le dossier contenant les fichiers de polices TrueType, et une taille.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| font_family_name | `str` | Le nom de la famille de police. |
| folder_path | `str` | Chemin du dossier contenant les fichiers de police TrueType. |
| size | `float` | La taille de la nouvelle police. |
| style | `FontStyle` |  |

### Exemple

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

### Voir aussi
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
