---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) class.

```python
def __init__(self):
    ...
```

### Example

```python
import groupdocs.watermark as gw

load_options = gw.PdfLoadOptions()
```

## __init__ {#password}

Initializes a new instance of the [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) class with a specified password.

```python
def __init__(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | `str` | The password for opening an encrypted document. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    print(pdf_content.pages[0].width)
    print(pdf_content.pages[0].height)
```

### See Also
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
