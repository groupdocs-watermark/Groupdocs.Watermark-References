---
title: "page_margin_type propriété"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Les marges de page pdf à utiliser lors de l'ajout de filigrane."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Les marges de page pdf à utiliser lors de l'ajout de filigrane.

Cette propriété ne fonctionne que lorsque [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) est définie sur True. Si elle est False, le CropBox du PDF est utilisé comme zone de filigrane.

La valeur par défaut est `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Voir aussi
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
