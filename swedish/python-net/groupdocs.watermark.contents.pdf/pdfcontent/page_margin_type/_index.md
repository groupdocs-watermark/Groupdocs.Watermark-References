---
title: "page_margin_type egenskap"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Pdf-sidmarginalerna som ska användas vid tillägg av vattenmärke."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Pdf-sidmarginalerna som ska användas vid tillägg av vattenmärke.

Denna egenskap fungerar endast när [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) är satt till True. Om den är False används PDF CropBox som vattenmärkningsområde.

Standardvärdet är `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Se även
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
