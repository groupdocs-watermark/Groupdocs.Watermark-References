---
title: "page_margin_type Eigenschaft"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Die PDF-Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden sollen."
type: docs
url: /de/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Die PDF-Seitenränder, die beim Hinzufügen von Wasserzeichen verwendet werden sollen.

Diese Eigenschaft funktioniert nur, wenn [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) auf True gesetzt ist. Wenn sie False ist, wird das PDF CropBox als Wasserzeichenbereich verwendet.

Der Standardwert ist `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Siehe auch
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
