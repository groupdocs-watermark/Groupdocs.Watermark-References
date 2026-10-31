---
title: "page_margin_type properti"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Margin halaman pdf yang akan digunakan saat menambahkan watermark."
type: docs
url: /id/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Margin halaman pdf yang akan digunakan saat menambahkan watermark.

Properti ini hanya berfungsi ketika [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) diatur ke True. Jika diatur ke False, PDF CropBox akan digunakan sebagai area watermark.

Nilai default adalah `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Lihat Juga
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
