---
title: "Font klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een lettertype voor."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Stelt een lettertype voor.

Het type Font geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Initialiseert een nieuw Font‑exemplaar met de opgegeven lettertypefamilienaam en grootte. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initialiseert een nieuw Font‑exemplaar met de opgegeven lettertypefamilienaam, grootte en stijl. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initialiseert een nieuw Font‑exemplaar met een aangepaste lettertypefamilienaam, een map met TrueType-lettertypen, een grootte en een stijl. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initialiseert een nieuw Font‑exemplaar met een aangepaste lettertypefamilienaam, de map met de TrueType-lettertypebestanden, en een grootte. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Het lettertype is vet. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | De familienaam van dit Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | De map die TrueType-lettertypebestanden bevat. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Het lettertype is cursief. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | De grootte van dit lettertype. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Het lettertype geeft een horizontale lijn door de tekst aan. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | De stijlinformatie voor dit lettertype. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Het lettertype is onderstreept. |

### Voorbeeld

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
Taakgidsen die `Font` gebruiken:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Zie ook
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
