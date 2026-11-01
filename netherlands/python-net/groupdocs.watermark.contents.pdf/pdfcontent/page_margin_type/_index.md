---
title: "page_margin_type eigenschap"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "De pdf-paginamarges die gebruikt worden tijdens het toevoegen van een watermerk."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

De pdf-paginamarges die gebruikt worden tijdens het toevoegen van een watermerk.

Deze eigenschap werkt alleen wanneer [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) is ingesteld op True. Als het False is, wordt de PDF CropBox gebruikt als het watermerkgebied.

De standaardwaarde is `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Zie ook
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
