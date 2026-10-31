---
title: "Classe Font"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un carattere."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Rappresenta un carattere.

Il tipo Font espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Inizializza una nuova istanza di Font con il nome della famiglia di caratteri e la dimensione specificati. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Inizializza una nuova istanza di Font con il nome della famiglia di caratteri, la dimensione e lo stile specificati. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Inizializza una nuova istanza di Font con un nome di famiglia di caratteri personalizzato, una cartella contenente font TrueType, una dimensione e uno stile. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Inizializza una nuova istanza di Font con un nome di famiglia di caratteri personalizzato, la cartella contenente i file di font TrueType e una dimensione. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Il font è in grassetto. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Il nome della famiglia di questo Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | La cartella che contiene i file di font TrueType. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Il carattere è in corsivo. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | La dimensione di questo Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Il font specifica una linea orizzontale attraverso il testo. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Le informazioni di stile per questo Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Il font è sottolineato. |

### Esempio

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
Guide operative che usano `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Vedi anche
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
