---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas PdfLoadOptions."
type: docs
url: /id/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/).

```python
def __init__(self):
    ...
```

### Contoh

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

Menginisialisasi instance baru dari kelas [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) dengan kata sandi yang ditentukan.

```python
def __init__(self, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | `str` | Kata sandi untuk membuka dokumen terenkripsi. |

### Contoh

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

### Lihat Juga
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
