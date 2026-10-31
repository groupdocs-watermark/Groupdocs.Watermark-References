---
title: "Classe Font"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente une police."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Représente une police.

Le type Font expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Initialise une nouvelle instance de Font avec le nom de famille de police et la taille spécifiés. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initialise une nouvelle instance de Font avec le nom de famille de police, la taille et le style spécifiés. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initialise une nouvelle instance de Font avec un nom de famille de police personnalisé, un dossier contenant des polices TrueType, une taille et un style. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initialise une nouvelle instance de Font avec un nom de famille de police personnalisé, le dossier contenant les fichiers de polices TrueType, et une taille. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | La police est en gras. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Le nom de famille de cette Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | Le dossier qui contient les fichiers de polices TrueType. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | La police est en italique. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | La taille de cette Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | La police indique une ligne horizontale à travers le texte. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Les informations de style pour cette Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | La police est soulignée. |

### Exemple

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
Guides de tâches qui utilisent `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Voir aussi
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
