---
title: "свойство page_margin_type"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Поля страниц PDF, которые будут использоваться при добавлении водяного знака."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Поля страниц PDF, которые будут использоваться при добавлении водяного знака.

Это свойство работает только когда [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) установлено в True. Если оно False, используется PDF CropBox в качестве области для водяного знака.

Значение по умолчанию — `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### См. также
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
