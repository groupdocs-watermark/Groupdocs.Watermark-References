---
title: page_margin_type property
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 90
---

## page_margin_type property


Gets or sets pdf page margins to be used during watermark adding.

### Remarks 


This property works only when [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark#consider_parent_margins) is set to true.
If [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark#consider_parent_margins) is false, when pdf CropBox is used as
watermarking area.


The default value is [`PdfPageMarginType.TRIM_BOX`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpagemargintype#TRIM_BOX).
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
* module [`groupdocs.watermark.contents.pdf`](../../)
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent)
* class [`PdfPageMarginType`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpagemargintype)
