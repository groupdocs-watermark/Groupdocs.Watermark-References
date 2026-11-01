---
title: "Clase Font"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una fuente."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Representa una fuente.

El tipo Font expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Inicializa una nueva instancia de Font con el nombre de familia de fuente y el tamaño especificados. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Inicializa una nueva instancia de Font con el nombre de familia de fuente, el tamaño y el estilo especificados. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Inicializa una nueva instancia de Font con un nombre de familia de fuente personalizado, una carpeta que contiene fuentes TrueType, un tamaño y un estilo. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Inicializa una nueva instancia de Font con un nombre de familia de fuente personalizado, la carpeta que contiene los archivos de fuentes TrueType, y un tamaño. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | La fuente está en negrita. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | El nombre de familia de este Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | La carpeta que contiene archivos de fuentes TrueType. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | La fuente está en cursiva. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | El tamaño de esta fuente. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | La fuente especifica una línea horizontal a través del texto. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | La información de estilo para esta fuente. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | La fuente está subrayada. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Guías de tareas que usan `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ver también
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
