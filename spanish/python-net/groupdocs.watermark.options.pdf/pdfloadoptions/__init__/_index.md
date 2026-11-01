---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PdfLoadOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

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

Inicializa una nueva instancia de la clase [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) con una contraseña especificada.

```python
def __init__(self, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | `str` | La contraseña para abrir un documento cifrado. |

### Ejemplo

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

### Ver también
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
