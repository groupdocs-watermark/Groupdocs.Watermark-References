---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de PdfLoadOptions klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert een nieuw exemplaar van de [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) klasse met een opgegeven wachtwoord.

```python
def __init__(self, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | `str` | Het wachtwoord om een versleuteld document te openen. |

### Voorbeeld

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

### Zie ook
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
