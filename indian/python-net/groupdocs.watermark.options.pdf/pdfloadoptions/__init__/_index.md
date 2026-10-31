---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "PdfLoadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) वर्ग का नया उदाहरण आरंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

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

[`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) वर्ग का नया उदाहरण निर्दिष्ट पासवर्ड के साथ आरंभ करता है।

```python
def __init__(self, password):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| password | `str` | एन्क्रिप्टेड दस्तावेज़ खोलने के लिए पासवर्ड। |

### उदाहरण

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

### संबंधित देखें
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
