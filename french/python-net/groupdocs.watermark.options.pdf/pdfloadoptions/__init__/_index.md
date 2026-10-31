---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe PdfLoadOptions."
type: docs
url: /fr/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/).

```python
def __init__(self):
    ...
```

### Exemple

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    print(pdf_content.pages[0].width)
    print(pdf_content.pages[0].height)
```

## __init__ {#password}

Initialise une nouvelle instance de la classe [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) avec un mot de passe spécifié.

```python
def __init__(self, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| password | `str` | Le mot de passe pour ouvrir un document chiffré. |

### Exemple

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    print(pdf_content.pages[0].width)
    print(pdf_content.pages[0].height)
```

### Voir aussi
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
