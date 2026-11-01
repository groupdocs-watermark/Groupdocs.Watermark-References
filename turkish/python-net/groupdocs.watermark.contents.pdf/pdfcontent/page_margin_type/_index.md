---
title: "page_margin_type özelliği"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigran eklenirken kullanılacak pdf sayfa kenar boşlukları."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Filigran eklenirken kullanılacak pdf sayfa kenar boşlukları.

Bu özellik yalnızca [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) True olarak ayarlandığında çalışır. False ise, PDF CropBox filigran alanı olarak kullanılır.

Varsayılan değer `PdfPageMarginType.trim_box`'dır.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
