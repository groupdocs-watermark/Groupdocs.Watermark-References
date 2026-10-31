---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Font-Instanz mit dem angegebenen Schriftfamiliennamen und der Größe."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Initialisiert eine neue Font-Instanz mit dem angegebenen Schriftfamiliennamen und der Größe.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_family_name | `str` | Der Name der Schriftfamilie. |
| size | `float` | Die Größe der neuen Schriftart. |

### Beispiel

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

Initialisiert eine neue Font-Instanz mit dem angegebenen Schriftfamiliennamen, der Größe und dem Stil.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_family_name | `str` | Der Name der Schriftfamilie. |
| size | `float` | Die Größe der neuen Schriftart. |
| style | `FontStyle` | Der Stil der neuen Schriftart. |

### Beispiel

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Initialisiert eine neue Font-Instanz mit einem benutzerdefinierten Schriftfamiliennamen, einem Ordner, der TrueType-Schriften enthält, einer Größe und einem Stil.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_family_name | `str` | Der Name der Schriftfamilie. |
| folder_path | `str` | Ordnerpfad, der TrueType-Schriftdateien enthält. |
| size | `float` | Die Größe der neuen Schriftart. |

### Beispiel

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

Initialisiert eine neue Font-Instanz mit einem benutzerdefinierten Schriftfamiliennamen, dem Ordner, der die TrueType-Schriftdateien enthält, und einer Größe.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_family_name | `str` | Der Name der Schriftfamilie. |
| folder_path | `str` | Ordnerpfad, der TrueType-Schriftdateien enthält. |
| size | `float` | Die Größe der neuen Schriftart. |
| style | `FontStyle` |  |

### Beispiel

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

### Siehe auch
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
