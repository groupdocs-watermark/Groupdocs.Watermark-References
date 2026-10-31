---
title: "خاصية page_margin_type"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "هوامش صفحة PDF التي ستُستخدم أثناء إضافة العلامة المائية."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

هوامش صفحة PDF التي ستُستخدم أثناء إضافة العلامة المائية.

هذه الخاصية تعمل فقط عندما يتم تعيين [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) إلى True. إذا كان False، يتم استخدام CropBox الخاص بـ PDF كمنطقة وضع العلامة المائية.

القيمة الافتراضية هي `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### انظر أيضًا
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
