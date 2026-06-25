---
title: page_margin_type property
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

The PDF page margins to be used during watermark adding.

Works only when [`Watermark.ConsiderParentMargins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) is True; otherwise the PDF CropBox is used as the watermarking area.

The default value is `PdfPageMarginType.TrimBox`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### See Also
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
