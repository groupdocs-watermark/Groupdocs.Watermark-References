---
title: "Font-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar ett typsnitt."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Representerar ett typsnitt.

Font-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Initierar en ny Font-instans med det angivna teckensnittsfamiljenamnet och storleken. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initierar en ny Font-instans med det angivna teckensnittsfamiljenamnet, storleken och stilen. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initierar en ny Font-instans med ett anpassat teckensnittsfamiljenamn, en mapp som innehåller TrueType-teckensnitt, en storlek och en stil. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initierar en ny Font-instans med ett anpassat teckensnittsfamiljenamn, mappen som innehåller TrueType-teckensnittsfilerna och en storlek. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Teckensnittet är fetstil. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Familjenamnet för detta Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | Mappen som innehåller TrueType-teckensnittsfiler. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Teckensnittet är kursivt. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | Storleken på detta Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Teckensnittet specificerar en horisontell linje genom texten. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Stilinformationen för detta Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Teckensnittet är understruket. |

### Exempel

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
Uppgiftsguider som använder `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Se även
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
