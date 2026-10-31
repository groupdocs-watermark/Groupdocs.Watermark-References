---
title: "Font-Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt eine Schriftart dar."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Stellt eine Schriftart dar.

Der Typ Font stellt die folgenden Member bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Initialisiert eine neue Font-Instanz mit dem angegebenen Schriftfamiliennamen und der Größe. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Initialisiert eine neue Font-Instanz mit dem angegebenen Schriftfamiliennamen, der Größe und dem Stil. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Initialisiert eine neue Font-Instanz mit einem benutzerdefinierten Schriftfamiliennamen, einem Ordner, der TrueType-Schriften enthält, einer Größe und einem Stil. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Initialisiert eine neue Font-Instanz mit einem benutzerdefinierten Schriftfamiliennamen, dem Ordner, der die TrueType-Schriftdateien enthält, und einer Größe. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Die Schrift ist fett. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Der Familienname dieser Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | Der Ordner, der TrueType-Schriftdateien enthält. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Die Schrift ist kursiv. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | Die Größe dieser Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Die Schrift legt eine horizontale Linie durch den Text fest. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Die Stilinformationen für diese Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Die Schrift ist unterstrichen. |

### Beispiel

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
Aufgabenleitfäden, die `Font` verwenden:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Siehe auch
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
