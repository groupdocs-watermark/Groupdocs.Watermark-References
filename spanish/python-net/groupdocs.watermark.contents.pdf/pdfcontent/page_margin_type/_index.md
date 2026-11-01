---
title: "propiedad page_margin_type"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Los márgenes de página pdf que se usarán al añadir la marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Los márgenes de página pdf que se usarán al añadir la marca de agua.

Esta propiedad funciona solo cuando [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) está establecida en True. Si está en False, se utiliza el CropBox del PDF como área de marca de agua.

El valor predeterminado es `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Ver también
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
