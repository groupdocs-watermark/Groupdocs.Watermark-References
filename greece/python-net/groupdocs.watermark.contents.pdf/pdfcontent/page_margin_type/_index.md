---
title: "ιδιότητα page_margin_type"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Τα περιθώρια σελίδας pdf που θα χρησιμοποιηθούν κατά την προσθήκη υδατογράφησης."
type: docs
url: /el/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/
is_root: false
weight: 2020
---


## page_margin_type property

Τα περιθώρια σελίδας pdf που θα χρησιμοποιηθούν κατά την προσθήκη υδατογράφησης.

Αυτή η ιδιότητα λειτουργεί μόνο όταν το [`Watermark.consider_parent_margins`](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) είναι ορισμένο σε True. Εάν είναι False, το PDF CropBox χρησιμοποιείται ως περιοχή υδατογράφησης.

Η προεπιλεγμένη τιμή είναι `PdfPageMarginType.trim_box`.

### Definition:
```python
@property
def page_margin_type(self):
    ...
@page_margin_type.setter
def page_margin_type(self, value):
    ...
```

### Δείτε επίσης
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
