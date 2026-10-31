---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza di Font con il nome della famiglia di caratteri e la dimensione specificati."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Inizializza una nuova istanza di Font con il nome della famiglia di caratteri e la dimensione specificati.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_family_name | `str` | Il nome della famiglia del font. |
| size | `float` | La dimensione del nuovo carattere. |

### Esempio

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

Inizializza una nuova istanza di Font con il nome della famiglia di caratteri, la dimensione e lo stile specificati.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_family_name | `str` | Il nome della famiglia del font. |
| size | `float` | La dimensione del nuovo carattere. |
| style | `FontStyle` | Lo stile del nuovo carattere. |

### Esempio

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Inizializza una nuova istanza di Font con un nome di famiglia di caratteri personalizzato, una cartella contenente font TrueType, una dimensione e uno stile.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_family_name | `str` | Il nome della famiglia del font. |
| folder_path | `str` | Percorso della cartella che contiene file di caratteri TrueType. |
| size | `float` | La dimensione del nuovo carattere. |

### Esempio

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

Inizializza una nuova istanza di Font con un nome di famiglia di caratteri personalizzato, la cartella contenente i file di font TrueType e una dimensione.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_family_name | `str` | Il nome della famiglia del font. |
| folder_path | `str` | Percorso della cartella che contiene file di caratteri TrueType. |
| size | `float` | La dimensione del nuovo carattere. |
| style | `FontStyle` |  |

### Esempio

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

### Vedi anche
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
