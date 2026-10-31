---
title: "proprietà page_margin_type"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "I margini della pagina PDF da utilizzare durante l'aggiunta della filigrana."
type: docs
url: /it/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

I margini della pagina PDF da utilizzare durante l'aggiunta della filigrana.

Questa proprietà funziona solo quando [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) è impostata su True. Se è False, il PDF CropBox viene utilizzato come area di filigrana.

Il valore predefinito è `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Vedi anche
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
