---
title: "PdfLoadOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει επιλογές φόρτωσης εγγράφου για ένα έγγραφο PDF."
type: docs
url: /el/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/
is_root: false
weight: 30
---


## PdfLoadOptions class

Αντιπροσωπεύει επιλογές φόρτωσης εγγράφου για ένα έγγραφο PDF.

Ο τύπος PdfLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/#password) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) με καθορισμένο κωδικό πρόσβασης. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Ο τύπος του αρχείου, που υποδεικνύει τη μορφή του (π.χ., docx, pdf, xlsx κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Η οικογένεια μορφής του εγγράφου, που υποδεικνύει τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    # εκτελεί λειτουργίες στον watermarker
    pass
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
