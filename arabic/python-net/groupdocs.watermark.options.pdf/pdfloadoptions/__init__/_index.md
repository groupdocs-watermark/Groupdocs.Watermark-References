---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثلاً جديداً من الفئة PdfLoadOptions."
type: docs
url: /ar/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلًا جديدًا للفئة [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/).

```python
def __init__(self):
    ...
```

### مثال

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

ينشئ مثيلًا جديدًا للفئة [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) باستخدام كلمة مرور محددة.

```python
def __init__(self, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | `str` | كلمة المرور لفتح مستند مشفر. |

### مثال

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

### انظر أيضًا
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
