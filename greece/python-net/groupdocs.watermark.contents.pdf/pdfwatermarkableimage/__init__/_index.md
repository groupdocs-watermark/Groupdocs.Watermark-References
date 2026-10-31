---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PdfWatermarkableImage χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας."
type: docs
url: /el/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας.

```python
def __init__(self, image_data):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_data | `list[int]` | Ο πίνακας των μη υπογεγραμμένων bytes από τα οποία δημιουργείται το `PdfWatermarkableImage`. |

### Παράδειγμα

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Δείτε επίσης
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
