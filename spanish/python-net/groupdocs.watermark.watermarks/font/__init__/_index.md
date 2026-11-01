---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de Font con el nombre de familia de fuente y el tamaño especificados."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Inicializa una nueva instancia de Font con el nombre de familia de fuente y el tamaño especificados.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_family_name | `str` | El nombre de la familia de fuentes. |
| size | `float` | El tamaño de la nueva fuente. |

### Ejemplo

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

Inicializa una nueva instancia de Font con el nombre de familia de fuente, el tamaño y el estilo especificados.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_family_name | `str` | El nombre de la familia de fuentes. |
| size | `float` | El tamaño de la nueva fuente. |
| style | `FontStyle` | El estilo de la nueva fuente. |

### Ejemplo

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Inicializa una nueva instancia de Font con un nombre de familia de fuente personalizado, una carpeta que contiene fuentes TrueType, un tamaño y un estilo.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_family_name | `str` | El nombre de la familia de fuentes. |
| folder_path | `str` | Ruta de carpeta que contiene archivos de fuentes TrueType. |
| size | `float` | El tamaño de la nueva fuente. |

### Ejemplo

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

Inicializa una nueva instancia de Font con un nombre de familia de fuente personalizado, la carpeta que contiene los archivos de fuentes TrueType, y un tamaño.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_family_name | `str` | El nombre de la familia de fuentes. |
| folder_path | `str` | Ruta de carpeta que contiene archivos de fuentes TrueType. |
| size | `float` | El tamaño de la nueva fuente. |
| style | `FontStyle` |  |

### Ejemplo

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

### Ver también
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
