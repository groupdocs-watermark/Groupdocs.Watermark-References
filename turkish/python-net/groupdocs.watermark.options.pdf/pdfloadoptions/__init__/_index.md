---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "PdfLoadOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

`[`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)` sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

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

Belirtilen bir parola ile [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | `str` | Şifreli bir belgeyi açmak için şifre. |

### Örnek

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

### Ayrıca Bakınız
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
